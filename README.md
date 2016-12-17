# GAAME

[(FUTURE) Heroku link][heroku]
[heroku]: https://www.heroku.com

![Product Flow](/docs/product_flow.png?raw=true "Product Flow")

## (NOT FINISHED) Design Docs
* [View Wireframes][wireframes]
* [API endpoints][api-endpoints]
* [Component Hierarchy][component-hierarchy]
* [Sample State][sample-state]
* [DB schema][schema]

[wireframes]: docs/wireframes
[api-endpoints]: docs/api-endpoints.md
[component-hierarchy]: docs/component-hierarchy.md
[sample-state]: docs/sample-state.md
[schema]: docs/schema.md

## Minimum Viable Product

GAAME is a... [description here]

- [ ] New account creation, login
- [ ] Landing pages
- [ ] "Cause": about, contact form
- [ ] BETA news feed / post upload for both players and coaches ("Show your gaame (i.e. cause, challenge, tip)")
- [ ] Video CRUD
- [ ] Video player
- [ ] Contact form

## Implementation Timeline
Note: Time estimates for each feature also include styling - so that when a feature is completed, it is fully styled, and completely bug-free and deployable.

### Phase 1: Design / UI / Hosting / Backend Setup and Front End User Authentication (0 hours, 01/01/01, 11:59pm)
**Objective:**
- Hosting on Heroku
- Register domain, configure DNS settings, email redirect
- Register account with CDN, upload sample videos for testing
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
