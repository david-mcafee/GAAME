# GAAME

[Heroku link][heroku]
[heroku]: https://www.heroku.com

## Design Docs
* [View Wireframes][wireframes]
* [API endpoints][api-endpoints]
* [Component Hierarchy][component-hierarchy]
* [Sample State][sample-state]
* [DB schema][schema]

[wireframes]: wireframes
[api-endpoints]: api-endpoints.md
[component-hierarchy]: component-hierarchy.md
[sample-state]: sample-state.md
[schema]: schema.md

## Minimum Viable Product

GAAME is a... [description here]

- [ ] New account creation, login
- [ ] Landing pages
- [ ] "Cause": about, contact form
- [ ] "Challenges" news feed / "Challenge" upload for both players and coaches
- [ ] Video CRUD
- [ ] Video player
- [ ] Contact form

## Implementation Timeline
Note: Time estimates for each feature also include styling - so that when a feature is completed, it is fully styled, and completely bug-free and deployable.

### Phase 1: Design / UI / Hosting / Backend Setup and Front End User Authentication (0 hours, 01/01/01, 11:59pm)
**Objective:**
- General site-wide styling / UI (4 hours)
- Initial set up / CDN / Github / front and back end secure authentication (2 hours)
- Rails back-end (database, tables, API) (2 hour)

### Phase 2: Landing Page / Navigation Bar / Footer (2 hours)
- Landing Page (.5 hours)
  - description, sample videos, testimonials, etc
- Navigation Bar (.5 hours)
- Footer (1 hour)
  - About
  - Contact (form)
  - FAQ
  - Social media links

### Phase 3: Videos Model, API, and Components (0 hours, 01/01/01, 11:59pm)

**Objective:**
- Video Index (3 hours)
- Video Upload (1 hour)

### Phase 3: Video Player (0 hours, 01/01/01, 11:59pm)
- Video Player (3 hours)

### Phase 4: Cause Info (0 hours, 01/31/17, 11:59pm)
- About Page (1 hour)
- Contact Form (1 hour)


### 1.0
- [ ] Subscriptions
- [ ] Forum
- [ ] Private webinars

### 2.0
- [ ] "Give" for "Cause"


Pages / Components
- Splash page
  - description, sample videos, testimonials, etc
- Home page (first page upon log in)
- Navigation bar
- Should this home page be the list of videos, or a user landing / profile page?
- Video List Component
- Will this have subcategories? Or just one list of videos? Kind of wondering if there are any proposed ideas for how this would look (I’d be glad to propose specific suggestions if there are none)
- Video Item
  - This could be a designated page, or a modal (i.e. “pop up”). Is there a preferences

- Player Challenge Videos
  - Player Challenge Component
    - Nested under each video item
- Is there a preference for Facebook comments / local comments?
- Footer
  - About
  - Contact (form)
  - FAQ
  - Social media links


- [ ] Production README
- [ ] Hosting on Heroku
- [ ] Basic design / implementation docs
- [ ] Register domain, configure domain and email redirect
  * Does NameCheap offer email?
- [ ] New account creation, login (require subscription) **
  - Player / Coach
- [ ]
- [ ] Footer? Social media icons and links **
- [ ] Video CRUD (available to admin only)
- [ ] Video hosting on CDN (Cloudinary or AWS)
- [ ] Playing videos (progress bar with continuous play)
   * I'm thinking implement as a modal
- [ ] Facebook integration page (or a Facebook-like wall) for challenge videos to be posted for and from players **
- [ ] User pages
   * Items: member since, photo, subscription end date
- [ ] Payment processing (Stripe or PayPal?)
   * Evaluate cost and benefits of Stripe vs. PayPal vs. other
   * Look into Koudoku gem for subscription handling
- [ ] User access to a Coaches portal page to schedule private webinars for coaching lessons / comments
- [ ] **Future Expansion**
  * Sign-up mailer
  * Video tags
  * Video comments
  * Video categories
  * Mailing list

### Notes:
 * Khan Academy badges, etc.
 * Name for product?
 * Primary technical challenges: payment processing, subscription service, video play, modals
 * Will need user terms and conditions, related to conduct, subscription, etc.
 * Find examples of good sports-related styling / fonts / color preferences
 * Learn to use React modal for video and forms
 * Could be helpful to have testimonials, inspirational quotes, bio, social media presence


Inspiration:
http://www.paulrabilexperience.com/
# GAAME
