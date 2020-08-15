# intu Pocket: **Loyalty earned, not bought**

***Fostering loyalty to keep customers coming back to intu's shopping centres***

With physical retailers folding at an unprecedented rate
and competition on the high street at an all time high,
how can 14 of the largest shopping centres in the UK keep footfall flowing all year round?
Simple, make shopping with intu a better deal than anywhere else.

> ***tl:dr: Fixed the map and created a cashback scheme leveraging behavioural techniques deliver xx% footfall, xx downloads and £xx revenue in x months.***

## The Challenge

To an omni-channel business like intu,
success in the face of a problem like this is multifaceted;
the app needs to encourage customers to visit frequently,
without becoming irritating,
it has to help them navigate a shopping mall,
without keeping their eyes glued to their phone
and most of all it has to feel honest, genuine and not like a con.

## The Solution
<!-- Show a before and after of the app, with Key stats in there -->
The intu Pocket app encourages loyalty
by paying visitors for every purchase at an intu shopping centre
— without asking them to change their shopping habits.
Simply signing up to the app starts earning you cash.

A flat cashback rate is guaranteed
and retailers are even able to create 'flash sales'
offering bonus cashback to drive footfall to their stores.

To encourage more frequent visits,
Pocket lets you know when your favourite brands are having a blowout,
and intelligently surfaces great deals
based on your shopping habits.
So if you’re a big fan of Costa,
you might get a little bonus reward the next time you walk past the café.

## The Journey

Mobile apps have the advantage of a built-in feedback platform,
so I kicked off the project with the app store reviews.
The reviews were harsh
but the pain-points were clear,
making the roadmap easy.
To create a set of prioritised, actionable objectives,
I ran a Review Planning workshop
with stakeholders,
distilling what stakeholders wished the reviews had said
into the following goals;
<!-- Show an image of the app store feedback -->
- Users should be happy with the core functionality of the app
- Users should want to recommend the app to others
- The app should look modern, trustworthy and "make joy"
- The app should have up-to-date content

Once those goals were met,
we agreed we'd be in a good place to start fostering loyalty.

### Fixing the wayfinding
<!-- Image of v2 of the app -->
By far the most common criticism was
that the app was useless for navigation
– its whole raison d'etre –
making that the top priority per our first goal.
Confusingly,
research from the brick-and-mortar CX team
indicated that centre visitors tend to follow habitual routes
and don't use maps,
so I had to interview app users
to understand why it was important to them.

It transpired that users weren't looking for directions per se,
but _information_ about _destinations_.
Sometimes opening times,
sometimes the nearest car park,
sometimes even a general location,
but rarely step-by-step directions.

Looking through the frame of destinations
I could plan out the solutions required.
First,
the map functionality needed to be fixed
and should better integrate store information,
then the IA and content strategy should be reviewed,
the UI should be polished
and finally,
processes put in place to make sure content would be up-to-date.

**~~[Read the wayfinding case study](/)~~** _Coming soon_

- Users found the new UI much easier on the eye, easier to read and easier to use on both Android and iOS. Using native patterns resulted in shorter development times.
- The simpler navigation puts important features front and centre, while the streamlined information architecture keeps secondary features easy to find.
- Now the hub of the app, the map is like a HUD for the shopping centre. Users can find store info without losing their position on the map.
- The app is designed offline-first, so when users hit those signal black-spots that even the in-centre Wi-Fi can't reach they don't lose their place.
- The app is connected to a new 'source of truth' API that keeps all intu's digital services in sync and up to date. **~~[See this project](/)~~** _Coming soon_
- The wayfinding function now has an 'Accessible Routes' setting,
for navigating with wheelchairs and pushchairs.

### Loyalty and personalisation
<!-- Image of v3 of the app -->
With users' core concern fixed,
the groundwork was laid to start cultivating loyalty.
At this point it was worth reconvening with stakeholders
and discussing what loyalty meant.
To intu, loyalty was defined as more frequent visits to centres.
This was decided because other metrics
like dwell time and footfall
would not be accurate measurements
and we wouldn't be able to measure visits to other shopping centres
(at least not ethically).
Visits to centres could easily be tracked in-app
and with the existing wi-fi
and beacon technology in centres.

To effectively shift behaviour,
I looked at the habits users already had
and tried to piggyback off them,
this way the new behaviour would be cued through existing habits.
Applying the Fogg Behaviour Model,
users were _motivated_ to shop and save,
I could give them the _ability_ to do so with an easy service
and I could _trigger_ the motivation using notifications.
By combining the offerings from other channels
and uncovering the motivations therein
I could bring offers, sales alerts, news, events and competitions all into one feed,
using engagement and location data
to promote what works best for that user.
To bolster this, users could also tailor their own profile.

**~~[See this project](/)~~** _Coming soon_

Ultimately the feed proposition was nixed
for not bringing anything unique to the table
and duplicating website functionality,
making the business value of a limited.
The idea was shelved
and I moved on to innovation exercises in the search for something more tantalising...

### Cashback

Given that most shopping centres
and high streets
have the same stores,
why would you pick one over the other?
Conventional wisdom points at convenience for the primary motivator,
but our user research indicates that financial benefit (discounts) is a strong motivator.

After running some innovation workshops
we decided to try a cashback scheme.
Leveraging the insight that
people are highly motivated by getting something for free,
this seemed like an effective trial for boosting loyalty.
We would reward shopping in our centres rather than at competitors',
paid for by retailers who would make up the difference in volume,
All retailers would benefit mutually from increased footfall
and on top of it all, intu would make some affiliate income.

This was a serious undertaking
that would require several third-party integrations
to bring the product to market quickly,
so that security was upheld
and to avoid having to register as any kind of financial institution.
I had to look around at similar market offerings
to define the requirements for the best experience,
then work with our team to figure out what was viable
with our time, budget and 3rd-party restrictions.
I also needed to iron out what the public would expect from a cashback scheme
so that our account managers could broker the right deals
(e.g. the same rewards across all centres, a simple system without tiers or restrictions).

**~~[See this project](/)~~** _Coming soon_

- Beta test / soft launch users responded positively to the cashback scheme
- Users were happy that they were being provided with enough value for the data they were giving up
- intu is better able to understand their user behaviours
- Users were significantly more likely to recommend the app, according to NPS scores.

### The shop / visual search

We had now a USP that would take other competitors significant research and investment to come to market with,
but there were still some areas where  competitors had an advantage.

Bringing intu's online shop and visual search to the app seemed to be a great opportunity to push another revenue stream
and the visual search could even convince shoppers in other stores to shop online with intu.

Translating the respective UIs from the web to the app was a relatively trivial job,
though other problems surfaced through the innovation cycle.
On the experience side,
users were more aware of the affiliate-link jump
given that the cognitive cost of switching to a webview is more than simply opening a new tab
and on the business side,
a conflict of interest was raised on behalf of the retail tenants who could lose revenue as the features encouraged users to shop online.
After estimating the effort of design and development,
plus the time to get retailers and hesitant stakeholders on board
we decided to shelve these features too
– we could always use webviews to bring the features in at a future date for testing.
Instead, we decided to put all our weight behind the cashback feature
and create a marketing strategy to increase awareness at launch.

### The new brand

The issue with the relauch of the app was in dealing with its negative legacy.
This includes both the app store reviews and the bad experiences of previous users.
We needed to come up with a solution that would really convince users that the app had turned around
and that they werent going to get burned a second time

After seeing the potential of reengagement campaigns from our pre-GDPR email activities,
it was clear that abandoning the 70,000 people with the app still installed would be reckless,
even if few were using it.

As a reaction to the dated and meek aesthetic of its predecessor
we would rename and comepletely restyle the app with something bold and contemporary
to draw a line between the old and new apps in our users' minds.
We would also run a soft launch at our smaller centres to live-test the app and gather feedback.
Users would be encouraged to download the app using ambient media and POS displays inside the shopping centres.
We also considered a pop-up store to show how easy using the app was.
By nudging the users to review the app after they recieved their £5 incentive
we hoped to improve the app rating and bury the negative reviews.
Using an agency the name 'Pocket' was introduced and style tiles created so we would know what tone and emotion the app should convey.
I ran some market testing using our deliverables to decide the final direction and then reskinned the app,
while the agency created the video assets we would use for the app store and marketing.
Inside the app a new onboarding screen as added to explain the new version of the app to existing users who, interest piqued by the name and icon change, reopened the app.

- The branding strategy was a success and few if any users related the two versions of the app
- Live testers responded positively and the app's rating skyrocketed at a cost of scarcely more than £5 per aquistion

## Results

intu Pocket has over 70,000 installs and XXX active users
and customers have responded to the launch by saying XXXXXXXXXX.
In the month after the soft-release the app's ranking shifted from #150 in Navigation to #113 in Shopping, reflecting the goodwill generated with the new and reengaged users.
Using the in-centre location tech intu is able to see how involvement with the rewards platform influences footfall for retailers for both flash offers and permanent rewards.
By combining that data with location and demographic data from the app they are now able to break footfall data down by cohort or demographic.
This will improve understanding of shopping habits in the aggregate
and enable personalisation across all of intu's touchpoints by attaching all that information to a user's account.

## Credit

- **Year:** 2017 – 2019
- **Company:** intu Digital
- **Team:** Tylen St Hilaire, Dean Barker Smith, Nologis (Agency), Moving Brands (Agency)
- **Fields:** UX, UI, Innovation
- **Industry:** Retail
