# Writing

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
