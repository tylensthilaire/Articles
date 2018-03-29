# Collaboration

## Multi-authoring

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

## Peer review

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