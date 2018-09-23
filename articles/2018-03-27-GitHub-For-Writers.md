---
title:  "GitHub For Writers"
author: "Tylen St Hilaire"
version: 0.4.0
updated: 2018-09-23
tags: [ GitHub, writing ]
---

# Github For Writers (Part 1)

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
and its methodical process 
could actually help you improve your writing – 
plus, it wont [read your private documents](https://www.telegraph.co.uk/technology/2017/11/01/google-reading-docs/) like Google.

_**TL;DR**
Incorporate GitHub into your workflow for better version control, collaboration and to improve your writing._

## Why

Have you ever wanted to try rewrite something you were working on completely differently? 
Maybe try a different plot path in a story you were writing? 
Reorganise the sections of a paper you were authoring? 
Or get ideas down while you were still researching? 
If so you've probably been let down by whatever desktop publishing software you normally use 
because you can't create different versions of what you were working on to try something new. 
You might even have written something then needed to go through pains to output it for the web or professional printing.

Well, theres something that solves all those problems, 
Enter GitHub.

...

Well, OK, GitHub alone can't solve all those problems 
*but* it is the foundation for dealing with them 
so if you want to discover and write iteratively 
or you like throwing around the words 'agile' and/or 'lean' 
you're in the right place.

## Getting started

Before you start writing 
you need to create a place for your prose to live. 

GitHub has two types of 'space' for your documents; 
repos (repositories) and [gists](https://help.github.com/articles/about-gists/), 
the main difference between them being that 
repos can contain folders and gists can't, 
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

With your _mise-en-space_ set you're ready to write. 

Cracking open your usual writing software 
and uploading those files to GitHub will work fine, 
but to get the most out of the tool 
you'll want to use [Markdown](https://daringfireball.net/projects/markdown/). 
The beauty of Markdown is that it 
removes fonts and styling from the equation 
so you can focus focus on writing and structure, 
just like drafting with pen and paper, 
and easily convert it to 
HTML, Microsoft Word, LaTeX 
and many other formats 
when it's time to publish. 

Markdown files can be edited _any_ text editor, 
so you won't be locked in to Google or Microsoft. 
Just name any text file you create like so, `file-name.md`, 
and you're all set, 
you can even do it right from GitHub. 

## Edit

GitHub's version control works by comparing differences ([diffs](https://help.github.com/articles/github-glossary/#diff)) 
between lines in old and new versions of a document. 
This works really great for code, 
but isn't ideal for spoken languages 
which 'soft-wrap' lines when we get to the edge of the page. 
Editing one word would show an entire paragraph as changed in GitHub, 
making it hard to compare specific edits.

An elegant solution for this 
is to use '[semantic line feeds](http://rhodesmill.org/brandon/2012/one-sentence-per-line/)'; 
by splitting sentences down into clauses 
and giving each thought its own line
it becomes easy to spot changes 
and move ideas around. 
Semantic line feeds create an almost poetic form, 
which, apart from looking quite beautiful, 
will help you isolate important ideas 
and simplify your language,
much the same way [*shisa kanko*](https://www.japantimes.co.jp/news/2008/10/21/reference/jr-gestures/#.VL7Xg-d2MTk) 
reduces mistakes on Japanese railways 
by creating a 'ritual' that drives attention to detail. 
Markdown and Semantic Linefeeds work perfectly together 
so you won't even need to reformat your text, 
it will transform back into paragraphs whenever you publish.

## Version Control

So the big thing about GitHub is version control. 
You can change anything, 
at any time, 
and always recover it.
Which is great, 
because your ideas are always evolving 
and besides, 
we live in the information age 
and it's easy continuously get new new information and feedback. 
Remember when Kanye released _The Life Of Pablo_ and [kept](https://pitchfork.com/news/64127-kanye-west-updates-the-life-of-pablo-in-tidal/) [updating](https://pitchfork.com/news/64176-kanye-west-updates-the-life-of-pablo-sia-and-vic-mensa-back-on-wolves-frank-ocean-gets-own-track/) [it](https://pitchfork.com/news/66109-kanye-once-again-is-updating-the-life-of-pablo-in-tidal/)? 
Well you can do the same. 
Just use the power responsibly. 
(You should always let people know if something has changed 
and where they can find old versions if needed.)

GitHub's version control model is called [GitHub Flow](https://guides.github.com/introduction/flow/),
basically, every repo can be split 
into a 'master' and 'branches'. 
A [branch](https://help.github.com/articles/github-glossary/#branch) is a copy of the repo 
where all your editing is done, 
keeping the master safe. 
You can even branch off a branch.
Whenever changes are required 
you create a new branch, 
change to that branch in GitHub desktop, 
open and make the changed to the files you want to edit, 
save the files, 
then '[commit](https://help.github.com/articles/github-glossary/#commit)' them back in GitHub desktop. 
A commit is like a save, 
but you can name and descibe them 
so if you ever need to go back and undo a change 
it's easy to find. 
When your changes are complete, approved, etc, 
You simply merge the branch back in to master 
*et voilà*, you are nolonger constrained to the realm of linear editing.

## Collaborate

GitHub is built for collaboration; 
specifically, peer review and multi-autoring. 
Both however have a learning curve 
so if your clients or team aren't clued in 
use whatever tool is most comfortable for everyone.

If your whole team is on board 
you'll first need to agree on some kind of model 
so that everyone uses branches the same way 
and don't overwrite each other. 
The most common model used is [GitFlow](https://nvie.com/posts/a-successful-git-branching-model/) 
but it was made for software development so you might want to simpify it.

So what's the benefit over, say, a shared Google Doc? 
Put simply, non-destructive editing. 
Although Gdocs allow you to see diffs on a word-by-word basis 
users can directly overwrite each other's changes 
and if you can't revert a change without losing every edit made afterwards.
With branches, each change is in it's own timeline so 
multiple people can work on multiple ideas at once.

## Publish

Once your manuscript is completed, 
you'll likely need to export it into a format you can use elsewhere. 
If you're writing for the web you're in luck, 
as most CMSs let you paste Markdown right in 
(free of those formatting errors you often get from Gdocs or Word).
For everything else, there's [Pandoc](http://pandoc.org); 
described as a 'Swiss Army knife' for document conversion, 
it will output your markdown in almost any format you need. 
including .docx for home publishing, 
.rtf for InDesign and InCopy, 
and LaTeX for academic submissions.

------

In the next articles in this series, we’ll walk through some gritty GitHub scenarios and cover more ways to improve your writing.

*Check out the full series: [GitHub For Writers](https://medium.com/@tylensthilaire_/), [Advanced GitHub For Writers](https://medium.com/@tylensthilaire_/),and [GitHub For Better Writers](https://medium.com/@tylensthilaire_/)*

*Spotted a mistake or got an improvement? [Create an issue on GitHub](https://github.com/tylensthilaire/articles)*

#### Summary

* Create a repo/gist for the manuscript

* Use Markdown for your writing



* Edit and preview right in GitHub

* Use branches to experiment with ideas safely

* Use Pandoc to export the article to the right publishing format

* Collaborate, improve and update as much as possible


#### Recommended reading

* [Writing Tech Articles by Jaakko Pallari](https://gist.github.com/jkpl/b2ec253dee7c97ff150487479a7cf7ba)
* [Writing With Github by Joe Buhlig](https://joebuhlig.com/writing-with-github/)
* [Top ten reasons GitHub is a great tool for creative writers](https://medium.com/@jjmerelo/top-ten-reasons-github-is-a-great-tool-for-creative-writers-d0e8b27de71d)
* [Waldir Pimenta's Semantic Linebreaker Tool](https://github.com/waldyrious/semantic-linebreaker)

------

####  Tylen is a Service Designer based in London.

*He works with multinational clients on omnichannel retail and b2b projects.*

*To see or read more a about him and his work, head to [tylensthilaire.com](https://tylensthiaire.com/), or [follow on Medium](https://medium.com/@tylensthilaire_). To do the same thing but with less commitment, head to [dribbble.com](https://dribbble.com/tylensthilaire) or [follow on Twitter](https://twitter.com/tylensthilaire).*