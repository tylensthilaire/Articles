# Setup

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