---
title:  "GitHub For Writers"
author: "Tylen St Hilaire"
version: 0.4.0
date: 2018-08-19
tags: [ Github, writing ]
---

# Github For Writers

GitHub is normally used for managing code 
across large teams, 
but it's just as good at managing your writing 
for the same reasons: 
it's available anywhere, 
collaboration is built in 
and it has change tracking at it's core.

Sure, 
it's not as frictionless as Google Docs 
but it allows for a looser writing flow 
and it's methodical process 
could actually help you improve your writing. 
It also wont [read your private documents](https://www.telegraph.co.uk/technology/2017/11/01/google-reading-docs/) like Google.

_**TL;DR**
Use the GitFlow workflow for better version control, collaboration and to improve your writing._

## Why

<!-- Section TBC -->

* have you ever wanted to try a different plot
* change something without losing
* reorganise your manuscript
* discover and write iteratively

## Getting started

Before you start writing 
you need to create a place for your prose to live. 
GitHub has two types of 'space' for your documents; 
repos (repositories) and [gists](https://help.github.com/articles/about-gists/), 
the main difference between them being that
repos can contain folders and gists can't 
but pricing and confidentiality is also a factor.
Secret gists are free for all users, 
but [aren't completely private](https://help.github.com/articles/about-gists/#secret-gists) – 
they don't show up publicly anywhere 
but anyone who discovers the URL _could_ see the contents – 
private repos on the other hand are completely private
but require a [premium plan](https://github.com/pricing).

For a minimalist use case a secret gist will work fine 
(you can always import it into a repo later),
but for professional use repos will be more convenient, 
particularly if you want to group or share documents 
per client or 'project'.

## Write

With your _mise-en-space_ set you're ready to get writing.

You could crack open your usual writing software 
and upload that to GitHub if you want, 
but to get the most out of the workflow 
you'll want to use [Markdown](https://daringfireball.net/projects/markdown/), 
just name any file you create on GitHub like so '`file-name.md`'. 
Markdown removes design from the equation 
to focus on writing and structure
without worrying about styling, 
but is easily converted to 
.html, Microsoft Word (.docx), LaTeX 
and many other formats for publishing. 
You'll also be able to open your documents in _any_ text editor 
so you're not walled in by Google or Microsoft, 
There are several extensions or 'flavours' of Markdown, 
[GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/) (GFM) is popular 
for obvious reasons, 
but [MultiMarkdown](http://fletcherpenney.net/multimarkdown/), 
has a more features 
(e.g. footnotes and references) 
suited to professional writing.

Although you can edit files online directly, 
for longer edits you'll want to do it locally in a nice text editor 
like GitHub's own [Atom](https://atom.io), [Lightpaper](https://getlightpaper.com), or [Typora](https://typora.io). 
But first you'll need to download (clone) and sync 
your files to your computer 
using [GitHub Desktop](https://desktop.github.com),
just find the clone url, hit 'Clone Repository' 
and you're ready to go.

## Write Better

<!-- Section TBC -->

While writing, 
you may want to make use of a [Scrivener](https://literatureandlatte.com/scrivener/overview)-style workflow 
by creating multiple smaller documents 
centred around a specific topic. 
You can also include a document for your outline, research, references, 
and so on. 
This non-linear writing method 
gets your ideas down as soon as inspiration strikes, 
and leaves the ordering of text until later, 
so your manuscript grows as organically as your thoughts do. 
You can completely polish one section 
while another sits in a bullet list 
and resructure your document whenever you like 
without feeling the pressure 
to make everything perfect right away.
Once you are finished writing, 
you simply copy-paste text 
from the individual documents 
into the main document 
(with the `yyyy-mm-dd-your-title.md` format) 
and clean up the files you don't need.

You might want to practice a little bit 
and do some background reading on [Git flow](https://guides.github.com/introduction/flow/) for versioning, 
but you'll be up and running in to time

GitHub's version control works by comparing differences (diffs) 
between lines in an old and new version of a document. 
This works really great for code, 
but isn't ideal for spoken languages 
because we typically write entire paragraphs on one line 
'soft-wrapping' the line when we run out of horizonal space. 
When comparing diffs 
editing one word would show an entire paragraph as changed 
making it hard to compare specific edits.

The workaround for this 
is to use a technique called '[semantic linefeeding](http://rhodesmill.org/brandon/2012/one-sentence-per-line/)'; 
by splitting sentences down 
into natural clauses and thoughts 
it becomes easy to see changes on each line 
and move ideas around. 
Semantic linefeeds will break your writing down 
into an almost poetic form 
which apart from looking quite beautiful 
will also help you isolate your important thoughts 
and simplify your language. 
Markdown and Semantic Linefeeds work perfectly together 
(despite being created in the 70's and 00's respectively) 
so you won't need to reformat your text, 
Markdown will transform it all back into paragraphs.

After your final draft is complete 
(release candidate in developer terms) 
I recommend combing though the manuscript 
to remove all nonessential phrases 
– made easier by the semantic linefeeds – 
and running it through [Hemingway](http://www.hemingwayapp.com). 
Hemingway's dedication to minimalism can make your writing sound mechanical though, 
don't let it tell you to drive into a lake.



the same way *shisa kanko* (pointing and calling) 
reduced mistakes on Japanese railways by [85%](https://www.japantimes.co.jp/news/2008/10/21/reference/jr-gestures/#.VL7Xg-d2MTk).

## Version Control

<!-- Section TBC -->

## Collaboration

<!-- Section TBC -->

### Multi-authoring

If you are working collaboratively 
you might want to consider using the more complex [Git Flow](https://nvie.com/posts/a-successful-git-branching-model/) 
which will help you manage changes 
more like a developer would. 
You can share the link to the gist 
other authors can then fork it 
and manage their own edits. 
When they are ready, 
you can merge their changes to your original Gist 
by adding the fork as a remote branch to your local repo, 
following the Git Flow process to get the changes to master, 
then pushing those changes to the original Gist.

You might wonder why you would invest in something so complex 
over something like a shared Google Doc. 
Put simply, non-destructive editing. 
Although Gdocs allow you to see diffs on a word-by-word basis 
users can directly overwrite each other's changes. 
You can use comments and suggestions to alleviate this 
but if you've ever looked into Gdocs version history 
you'll see how hard it is to find a specific change. 

Git Flow's branching model puts you into a 
version-control mindset 
by asking you to identify each 'task' you intend on completing in a branch 
and to name and describe each change in a commit. 
Isolating the branches allows you to merge only changes you accept 
regardless of when they were created 
Gdocs only has one timeline, 
so if you made a mistake in the past 
that you want to revert 
you can't without losing every other edit you've made afterwards.

### Peer review

Peer review is a different story. 
Although GitHub is perfect for letting other people change your text, 
if they just want to request a change 
the only sensible way to do that is with an issue 
which is only possible if you started with 
or have already imported your gist 
into a repo.

Regardless, 
the person reviewing is probably not going to be familar with GitHub 
so you might be just as well exporting out a version 
and allowing them to feedback in the way they are most comfortable.
If your clients are like mine 
and like Gdocs 
you can export you .md to .html 
then open the .html file in your browser 
and copy-paste the text into a Gdoc.

## Publishing

<!-- Section TBC -->

Once your manuscript is completed, 
you'll likely need to export it into a format you can use elsewhere. 
Many CMSs will let you copy and paste Markdown 
right into the content field for digital publishing 
but the format will depend on the specific output. 
[Pandoc](http://pandoc.org) is a great tool, 
described as a 'Swiss Army knife' for document conversion. 
You could even make use of 'continuous integration' 
and have your text compiled to multiple formats 
and deployed to multiple outputs 
with every merge to master.

If you're publishing directly to GitHub Pages 
you just need to make sure your post conforms to the Jekyll standards 
and either import your gist to the right repo and/or push your changes to master.

## Revisions

<!-- Section TBC -->

Once your work is published 
you can continue to revise it, 
Particularly for any public repos, 
GitHub makes this very easy. 
Readers can raise an issue to suggest improvements 
or fork your repo to make their own, 
which you can merge back into master.

Managing issues can be tricky if there are too many
and they're not fully fleshed out. 
The best way to manage these is to 
create a new issue for yourself 
that references the issue(s) that sparked the idea 
and close the originals. 
That keeps the issue under your control 
but still acknowledges the original contributor.

## Summary

<!-- Section TBC -->

* Create a gist for the article 

* Create a markdown file with the namespace `yyyy-mm-dd-article-title.md`.

  * Use GitHub Flavoured Markdown for best previews


  * Add YAML frontmatter to the file

* Clone the gist to your machine with GitHub desktop

* Edit the gist in your preferred editor

  * Use semantic linefeeds for readable edit histories
  * Use Scrivener-style chunking for non-linear writing

* Version control with GitHub flow

* When complete, concatonate all the files and import the gist to a repo; one per project/client

* Use Pandoc to export the article to the right publishing format

* Collaborate, improve and update your article using GitHub issues

  * Use semantic version control to denote changes

## Further reading

<!-- Section TBC -->

* [Writing Tech Articles by Jaakko Pallari](https://gist.github.com/jkpl/b2ec253dee7c97ff150487479a7cf7ba)
* [Writing With Github by Joe Buhlig](https://joebuhlig.com/writing-with-github/)
* [Top ten reasons GitHub is a great tool for creative writers](https://medium.com/@jjmerelo/top-ten-reasons-github-is-a-great-tool-for-creative-writers-d0e8b27de71d)
* [Import gist to repo](https://stackoverflow.com/questions/13671328/transfer-gist-repo-to-github/37144960#37144960)
* [Waldir Pimenta's Semantic Linebreaker Tool](https://github.com/waldyrious/semantic-linebreaker)

------

*Spotted a mistake or got an improvement? Create an issue on GitHub*
