---
title: Insert any .html in a GitHub README
description: You can work around GitHub-flavoured Markdown’s .html filters… if you dare.
date: 2022-01-31
readingTime: 3:00
tags: ["Front-end"]
version: 1.0.0
---

# Insert any .html in a GitHub README

**TLDR:**
Using `<svg>` and its `<foreignObject>` element,
you can skirt GitHub's .html sanitization
and use the full .html spec —
though you still probably shouldn’t.

Reasons to insert disallowed .html into them have always existed,
though most were satisfied with the constraints.
Since GitHub enabled profile READMEs,
those reasons have,
for better or worse, ballooned.

Many profile READMEs eschew the minimalism intrinsic to Markdown
and instead evoke the halcyon chaos of Geocities, MySpace and Tumblr.
Trends are, if nothing else, cyclical.
There’s no accounting for taste when it comes to expressing individuality,
though we need not repeat _all_ the sins of the past.

I’m talking about text in images. It’s inaccessible, don’t do it.

But that doesn’t mean you can’t have your cake and eat it —
providing you’re okay with the risk of pushing constraints.

Here be dragons.

## Inserting a foreign object

`<foreignObject>` is an .svg element which may elements from a different .xml namespace.
Because .html is extended to .xhtml,
we can functionally insert .(x)html with the following:

```xml
<svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <html xmlns="http://www.w3.org/1999/xhtml">
      <head>
        <style><!-- Your styles here --></style>
      </head>
      <body>
        <!-- Your content here -->
      </body>
    </html>
  </foreignObject>
</svg>
```

You'll need to follow the .xhtml spec to make this work,
which has a few quirks
– all elements require closing tags, all attributes require values – though in theory your only limits are the properties of the .svg’s parent element.
Or GitHub closing this loophole with extreme prejudice.

Fair warning,
if you’re going to insert foreign objects,
do so at your own risk.
(This is always good advice.)

## The loophole in action

Bringing it all together is trivial:
host the .svg file in the repo, a gist,
or anywhere with cross-origin resource sharing.
Then, insert it in the README.md with.
Be sure _not_ to include alt text if you’re inserting an .svg with text in.

For this example,
I’ve approximated one of the [GitHub stats cards](https://github.com/anuraghazra/github-readme-stats#all-demos),
but you should be able to make something as simple or complex as you like.

<script src="https://gist.github.com/tylensthilaire/d4690f6edc83f8be1f772110d8cc1640.js"></script>

[View the Gist on GitHub](https://gist.github.com/tylensthilaire/d4690f6edc83f8be1f772110d8cc1640")

You have full control to make anything you can in regular .html:
styles, media queries, animation, anything you think of, you can hack in.
But most importantly,
there's no excuse for any inaccessible text in images.

## Crib sheet

Thanks to .xhtml you can insert .html anywhere you can place an .svg by:

1. adding a `<foreignObject>` element to your .svg
2. adding a container with the xhtml namespace inside the `<foreignObject>`
3. adding your .html and styles inside the container
4. placing the .svg somewhere you can reference it and including it in the README
