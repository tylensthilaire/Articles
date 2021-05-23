# Content management lifecycles for the modern web

**TLDR:** The trend of increasing complexity in media platforms requires a more flexible,
future-proof framework than any existing linear model.

Creating content is no longer a two step process of editing and publishing to the web[^As proposed by Susan McKeever in her 2003 paper [Understanding Web content management systems: evolution, lifecycle and market](https://www.researchgate.net/publication/220672404_Understanding_Web_content_management_systems_evolution_lifecycle_and_market)].
As web content has matured from hypertext documents into rich media,
content delivery processes have had to evolve beyond that of the traditional editorial workflow.

A modern digital product likely contains several content types (*entities*) to be managed. 
A typical brochureware website might contain evergreen pages, products and articles. 
A music streaming service might have artists, albums, songs, playlists, reviews, genres, composers and so on. 
Every product is built from a dense network of interrelated entities,
each with its own lifecycle.

## Why content lifecycles are important

Authoring *tools* are evolving to meet the requirements of this new paradigm[^as anyone with a headless CMS or excited about [MACH ecosystems](https://machalliance.org/) will know],
but authoring *practices* are yet to catch up.

The content lifecycle
(or content delivery workflow)
affects not only how content is published
but technology choices and user-experience.
Because of its broad impact, each lifecycle must, at least, address:

- how content is sourced, approved and maintained
- who should have what editing privileges
- how entity relationships affect each other — for example, if reviews are deleted when an account is deleted
- which entities to manage through which systems — for example, separating products and articles into separate CMSs
- what user-facing states entities go though — for example: coming soon, available, sold out.

Without clear definition and consensus on these requirements,
you will be unable to efficiently create content and risk costly business process and technology changes.

## How it's done

To deal with increased complexity of requirements,
proposals succeeding McKeever's work espouse workflows with an increasing litany of linear steps.
Unfortunately, their rigidity rarely suits the real-world needs of complex content models and organizational structures,
making adoption challenging.
Instead, a model framework of requirements to be combined into a custom workflow
— linear or otherwise —
is better suited to modern requirements.

‘Idealised’ linear processes aren’t all bad though,
they provide a digestible framework for categorising requirements.
There are always edge-cases,
but a typical content lifecycle will pluck requirements from 6 stages:

- Plan
- Produce
- Publish
- Promote
- Maintain
- Decommission

Involving all stakeholders in the design of your organisation's content lifecycles is essential to their success.
They will likely touch multiple departments: marketing, design, development, even operations.
As with any cross-departmental effort, early involvement is key instilling a sense of ownership;
and that alignment is key to your lifecycles’ viability.

Finally, you should monitor your content lifecycles.
Plan how you’ll iterate and what triggers an iteration.
Consider your response to bottlenecks, scale, strategy shifts and new technology[^AI-assisted copywriting startups are booming, see [Spell.ai](https://spell.tools/), [Copy.ai](https://www.copy.ai/), [Writesonic](https://writesonic.com/), [Copysmith](https://www.copysmith.ai/), [ABtesting.ai](https://abtesting.ai/) and [Copy Rocket](https://www.copyrocket.ai/) to name a few. And if this [AI authored article](https://www.theguardian.com/commentisfree/2020/sep/08/robot-wrote-this-article-gpt-3)) from the Guardian is anything to go by, it won’t be long before [GPT-3](https://gpt3.website/) goes mainstream.].
Planning for change will build adaptability into your system,
ensuring a long, stable life in a constantly shifting landscape.

## Stages Of A Content Lifecycle Framework

Although presented with an implied chronology,
the stages of this framework are not strictly linear.
Each stage is a category of activities,
to be completed in the order that best fits your content’s needs
– or not at all.
Although there are implicit dependencies,
an Agile approach will minimise bottlenecks and blockers.
Identify which dependencies are start-first rather than end-first and try to parallelise as many activities as is sensible.
Once you have selected the required activities for your lifecycle and ironed out all the conditions and iterative loops, 
the best way to present it is with a service blueprint.
A blueprint will not only help your stakeholders visualise who is involved and when,
alongside the technology needed to support it.
When you want to improve your lifecycles,
that blueprint will be the starting point for your user journey map.

### Plan

Due to the differences in value of each content type,
planning steps vary between different types.
All however have the same key theme:
‘what content *don’t* we need?’.
Creating content is not the hard part,
ideas are cheap.
Creating the *right* content is hard
– and to find that you need a set of filters:

- alignment with OKRs
- meeting user needs
- opportunity
- success measures
- organisation

Your starting place is a directive of some sort,
be it a vision statement,
a set of OKRs or a complete content strategy.
This is your first filter.
All content ideas
— whether articles on Wikipedia or movies on Netflix —
need to be in the aid of achieving organisational goals. 

The second filter is the user’s voice.
Who are you speaking to?
What need of theirs are you meeting?
If you’re not creating for a specific need,
you’re creating vanity content and wasting resources.

One you’ve proven there’s value in creating a content item,
you need to understand the opportunity.
How much value will it bring?
This is typically achieved through auditing and analysis of engagement stats (sales or traffic), keyword research, or competitor analysis.
What content do you have?
What else exists?
How are they performing?
These questions will help you to decide whether to create something new, repurpose or repush something else.

The next thing to consider are your success measures.
You might have departmental KPI’s,
or you might create specific criteria for a content type or item.
Either way,
set a realistic target and a reasonable time frame to check that your content is performing as well as intended.

When creating an entirely new content type,
you’ll also need to consider your information architecture and content model.
How will the structure and navigation of your site need to change to fit this new content?
What attributes need to be defined,
e.g. to ensure content is searchable, or to use it in recommendations?
How does it relate to other content types
e.g. if a user deactivates their account what happens to their reviews?
You may even choose to manage content in different platforms
– it’s unlikely that the interface you make pages with is the interface you want to manage product with.
Be sure to think about the future,
the better your initial setup,
the lest costly any transformations will be. 

Once you have gathered and analysed all your evidence,
you can put together a content plan to share with stakeholders for approval
before progressing to content production.

### Produce

Once the preparatory work is completed,
you a can begin content production.
This is everything you need to do to get it ready for publishing,
typically including:

- research
- asset collation 
- authoring
- internationalisation
- editing
- metadata

The goal of these steps is to produce quality,
trustworthy content.

Research is the first step to ensuring that what you are producing is trustworthy. 

Most content types will require some level of background information,
though research lends itself much more to knowledge-base or opinion content,
as opposed to product or media content.

In an ideal situation,
you will use a combination of primary and secondary research sources.
Unfortunately the effort to produce primary research is often prohibitive.
If that is the case for you,
put extra scrutiny on your secondary sources to ensure your information is valid.

When using secondary research be sure to evaluate the quality of your sources consider:
the authors credibility, biases and affiliations;
the level of detail and interpretation;
how current the information is and the editorial quality.

Finally you find yourself broaching the most obvious aspect of the content lifecycle:
collation and authoring.
Here you write, draw, record or otherwise create your original content,
and combine your media into a single, useful package.
You may also need to relate your entity to other entities to pull in extra content
(e.g. songs to albums, pulling in album art).
Remember to follow your organisation’s style guide
and graphic standards.

For the technical aspects of the content,
e.g. metadata and accessibility you may need to work with other disciplines,
e.g. UX and SEO to make sure your content is easy to find and use. 

Once you reach a draft your content you’re comfortable with,
ask a second person to review it and check for errors.

This peer review process should weed out factual inaccuracies and oversights in
style, reading level, tone and structure
— though not necessarily all by the same person.
For complex or technical topics a subject matter expert should be responsible for the facts,
while editorial and design staff own the rest.

It’s normal to loop though editing and reviewing more than once before reaching a proof-ready state.
To cut down the elapsed time of this cycle,
consider creating a peer review checklist and pair writing
— creating and editing content side-by-side with a reviewer.
When creating international and multi-language content,
remember to work closely with a translator
and be considerate of the cultural context.

Producing rich-media is innately harder than simply putting pen to paper and letting your thoughts flow,
there are just more moving parts.
In spite of all these extra considerations,
don’t lose focus on the purpose of your content.
Express a point of view,
bring something new to the conversation,
be memorable, be useful.

### Publish

Publishing as a lifecycle stage has remained fairly consistent over the years.
Largely because it is mostly handled offline.
The core aspects of publishing are:

- peer review
- workflows and approval
- scheduling

All content should have a 'sanity-check' review as a minimum before publishing.
Bring a fresh pair of eyes to the table to ensure that
images have alt text,
links are working,
tags are accurate
and so on. 

Complex organisations may need one or more approvals before publishing content,
such as by an editor or legal team.
You will need to decide whether adherence to that workflow should be enshrined in the CMS
or managed as a business process.
Each route has pros and cons
but both can be made to work,
even for large organisations.
Bear in mind that different content types may need different processes
— for example products and articles.

Once all checks are completed,
the final publishing consideration is scheduling.
Product releases may need to be scheduled for specific days. 
Articles for specific times.
User-generated content might be published immediately.
You will need to consider the needs of each publishing department
and integrate their processes into your content lifecycles.
If your service is distributed across multiple platforms,
additional governance may be needed
to deliver content to each.

### Promote

If appropriate,
you should think about how content is going to be promoted to users
and what other relevant websites or offline material should link to it.

Marketing and promotion is a discipline unto itself but there are some rules of thumb to consider.

- social media
- feeds

If you want to display different images, titles and other metadata on different social media channels
(e.g. to cater for different audience demographics on each) you’ll need to ensure that your Open Graph,
Twitter Card, Rich Pin and other metadata
can be edited separately and has sensible fallbacks.

If you want to support syndication or hook into ad networks you’ll usually need to supply a feed.
These are rarely complex and are well documented.
In many cases it’s just a matter of providing a URL with a CSV or XML file at the end of it with your feed data. 

### Maintain

Unlike printed media,
the web is made up of living documents.
Each content item can change over time and have a far greater reach than a book or brochure.
For that reason,
there are a few extra things to consider as part of your content lifecycle:

- reviewing and updating
- tracking changes
- measuring success

Updating content over time isn’t a new idea;
books receive updated editions, albums are remastered.
The difference between digital and physical content is the permanence of the artefact,
and how that affects a consumer’s relationship with it.

Each edition of a book will receive a unique ISBN,
each musical recording and release an ISRC and UPC.
These internationally standardised unique identifiers trivialise distinguishing between different editions of those pieces of content.
The fact that once printed or pressed the physical artefact can’t be changed notwithstanding. 

Digital media has no such system,
you can alter content indefinitely,
even after it is purchased.
In doing so,
you can erase the original version from existence without leaving a trace of history[^Take Kanye West’s *The Life of Pablo* for example. After releasing the album to the streaming service Tidal, [Kanye continued to alter tracks for around four months](https://en.wikipedia.org/wiki/The_Life_of_Pablo#Post-release_updates) (to praise and controversy). He described the work a “a living, breathing, changing, creative expression”.].
Usually, altering or updating content after publishing
will trigger a loop through your produce, publish and promote activities.

Because content can be updated in such a way,
you’ll need to decide if previous versions should be stored in some way,
and if they will be publicly available.
Government documents or financial records in a CRM are examples of content that tends to have a historical record.
Informational content may simply state the date it was updated and what changed.
These requirements and policies are why it’s important to involve
technical, legal and operations teams
in your lifecycle planning.

When content is created with a purpose,
it should be monitored to make sure it is fulfilling that purpose.
Decide how often you will audit content to ensure it is correct and meeting the success criteria you set out.
If it isn’t,
decide how you will handle that.
Either way,
you can use this information to update your content strategy.

If you do retain historical versions of your content,
it needs to be sensibly version controlled.
Implementation could be as simple as timestamped versions,
or it could be an adapted [Semantic Versioning](https://semver.org/) system with a visual diff. 

Complicating the matter,
some content represents a physical object that can go through different physical states:
a housing development might be proposed, planned, under construction, built;
or conceptual states:
a product might be coming soon, available, low in stock, sold out.
Those different states might require different content to describe,
or may even have completely different audiences and intent.
If so, each state might trigger a set of lifecycle activities.

### Decommission

Dealing with outdated content is the most overlooked aspect of content strategy.
Web content tends to be amaranthine,
lacking any indication of age.
Without that context,
readers are rarely able to tell what is up-to-date and what isn't.

To minimize misinformation
you should always decommission outdated content
by unpublishing or withdrawing. 

If a piece of content has reached the end of its useful life
— for example by making it harder to find relevant content –
it should be unpublished,
removing it from circulation.

When content is out-of-date but useful as a historical reference
it should be withdrawn instead.
Withdrawn content is left in circulation
but has an indicator that it is no-longer up-to-date.
See The Guardian’s content warning.

Alongside the standard approvals and communication with owners and stakeholders,
a robust decommissioning process must follow a few technical steps;
unpublished pages must respond with an appropriate http response status code;
either a 404,
such as when a page is no-longer relevant
or a 301,
such as when one page is consolidated into another.

The 301 will automatically redirect traffic from the old page to a new one.
A 404 page should help a visitor continue their journey as much as possible. 

It all cases
it should be clear whether unpublished pages are to deleted or archived.
For cases when the content ought to be a matter of public record
(such as in government)
an explanation of the removal may be required.
If a visitor is able access or request archived content,
they must be adequately informed of how to do so.

Collectively, 
these requirements ensure a good user-experience after the decommissioning
and prevent any negative effects on SEO.

## Conclusion

A great content lifecycle is much more than a process flow diagram;
it’s a commitment to a standard.
It defines not only what ‘good’ is,
but what success is,
and lays out the steps to get there.
Sharing a lifecycle connects disciplines;
unifing understanding of content delivery,
setting expectations,
and streamlining business processes.
All of which is achieved through content’s ultimate goal: improved communication.


## Crib sheet

Work with your stakeholders early on to get them involved in the design of your organisation’s content lifecycle. This will impress upon them:

- the benefits of good content strategy and design
- the amount of work that goes into a content item and the resource it needs
- the roles and responsibilities of everyone involved in the delivery of a content item – for example, content designers and subject matter experts
- You should monitor how your content lifecycle is working, and plan to iterate it to make improvements or changes.

Following a consistent content lifecycle helps your organisation create content that:

- provides user value
- is accurate and up-to-date
- is accessible and equitable 