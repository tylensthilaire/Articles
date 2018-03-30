---
title:      GitHub For Writers
author:     Tylen St Hilaire
date:       2018-03-27
version:    0.3.0
categories: article
tags:       GitHub, writing
©:
---

# Github For Writers

GitHub normally used for managing code 
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
can actually help you improve your writing, 
the same way *shisa kanko* (pointing and calling) 
reduced mistakes on Japanese railways by [85%](https://www.japantimes.co.jp/news/2008/10/21/reference/jr-gestures/#.VL7Xg-d2MTk). 
It also wont [read your private documents](https://www.telegraph.co.uk/technology/2017/11/01/google-reading-docs/) like Google.

```
**TL;DR**
Use GitHub and GitFlow for better version control and collaboration and maybe even to improve your writing.
```

## Setup

Before you start writing 
you need to create a place for your prose to live.
GitHub has two types of 'space' for your document to saved; 
repos (repositories) and [gists](https://help.github.com/articles/about-gists/) 
The main difference between a repo and a gist 
is that repos can contain folders 
and a gist can't. 
Secret gists are available for free to all GitHub users, 
unlike private repos, 
which makes them ideal for a writer's minimalist use case, 
but they [aren't private](https://help.github.com/articles/about-gists/#secret-gists) – 
they have obscure URLs and aren't indexed by search engines 
but anyone who has the URL can see the contents.

I recommend starting with a secret gist, 
then importing the gist into it's own directory (folder) 
in a repo.
Repos are either completely public or completely private. 
Because a collaborator can see everything in a repo, 
it often makes sense to create repos per client or per 'project'.

You can create the files for your gist in whatever text format you choose, 
but [Markdown](https://daringfireball.net/projects/markdown/) (.md) makes a lot of sense 
because it allows you to include formatting 
that GitHub will render automatically 
and which can be easily output to many other formats 
including .html, .opml, Microsoft Word (.docx), LaTeX 
and many others. 
There are several 'flavours' of Markdown which extend the original spec. 
[GitHub flavored Markdown](https://guides.github.com/features/mastering-markdown/) (GFM) is an obvious one, 
because it works perfectly with the GitHub platform 
but my personal favourite is [MultiMarkdown](http://fletcherpenney.net/multimarkdown/) 
as it's fully compatible with GFM 
but has a lot more features 
(e.g. footnotes and references) 
and is very well supported.

If you do choose markdown 
naming your file in the format `yyyy-mm-dd-your-title.md` 
will make it compatible with [Jekyll](https://jekyllrb.com). 
Jekyll powers [GitHub Pages](https://pages.github.com), 
so you can turn any repo into a website.
You can also add Jekyll-style [YAML frontmatter](https://jekyllrb.com/docs/frontmatter/) to the file, 
if you want to include important metadata 
like authors or publish dates. 
Even if you'll never need a GitHub Page, 
these conventions are a good best practice.

## Writing

Although you can edit a gist using the online editor, 
it's rare that you would want to 
except for the most minor edits. 
For longer edits you'll want to clone the gist (copy it to your computer) 
and edit it from there using your preferred text editor (e.g. GitHub's [Atom](https://atom.io)). 

While writing, you may want to make use of a [Scrivener](https://literatureandlatte.com/scrivener/overview)-style workflow 
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

GitHub makes version control easy with [GitHub Desktop](https://desktop.github.com). 
You might want to practice a little bit 
and do some background reading on the [GitHub flow](https://guides.github.com/introduction/flow/) for versioning, 
but you'll be up and running in to time.

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

## Collaboration

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

* [Writing Tech Articles by Jaakko Pallari](https://gist.github.com/jkpl/b2ec253dee7c97ff150487479a7cf7ba)
* [Writing With Github by Joe Buhlig](https://joebuhlig.com/writing-with-github/)
* [Top ten reasons GitHub is a great tool for creative writers](https://medium.com/@jjmerelo/top-ten-reasons-github-is-a-great-tool-for-creative-writers-d0e8b27de71d)
* [Import gist to repo](https://stackoverflow.com/questions/13671328/transfer-gist-repo-to-github/37144960#37144960)
* [Waldir Pimenta's Semantic Linebreaker Tool](https://github.com/waldyrious/semantic-linebreaker)



------

*Spotted a mistake or got an improvement? Create an issue on GitHub*