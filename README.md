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

MVP Features:
- [ ] New account creation, login
- [ ] Landing pages
- [ ] "Cause": about, contact form
- [ ] BETA news feed / post upload for both players and coaches ("Show your gaame (i.e. cause, challenge, tip)")
- [ ] Video CRUD
- [ ] Video player
- [ ] Contact form

## Implementation Timeline
Note: Time estimates for each feature also include styling - so that when a feature is completed, it is fully styled, and completely bug-free and deployable. Does not include time for research, debugging, etc.

### Phase 1: Design / UI / Hosting / Backend Setup and Front End User Authentication
####(13 hours, 12/25/16, 11:59pm)

**Objective:**
- Hosting on Heroku (.5 hours)
- Register domain, configure DNS settings, email redirect (.5 hours)
- Register account with CDN, upload sample videos for testing (.5 hours)
- General site-wide styling / UI (7.5 hours)
- Initial set up / CDN / Github / front and back end secure authentication (2 hours)
- Rails back-end (database, tables, API) (2 hours)

### Phase 2: Landing Page / Navigation Bar / Footer
####(2 hours, 12/28/16, 11:59pm)

**Objective:**
- Landing Page (.5 hours)
  - description, sample videos, testimonials, etc
- Navigation Bar (.5 hours)
- Footer and info pages (1 hour)
  - About
  - Contact (form)
  - FAQ
  - Social media links

### Phase 3: Videos Model, API, and Components
####(4 hours, 01/01/01, 11:59pm)

**Objective:**
- Video Index (3 hours)
- Video Upload (1 hour)

### Phase 3: Video Player
####(4 hours, 01/01/01, 11:59pm)

**Objective:**
- Video Player (4 hours)

### Phase 4: Cause Info
####(2 hours, 01/01/01, 11:59pm)

**Objective:**
- About Page (1 hour)
- Contact Form (1 hour)

### Total Billable Hours: 25

### 1.0
- [ ] News feed / possible Facebook integration
- [ ] Subscriptions / Payment
- [ ] Coach Forum
- [ ] Private webinars / scheduling

### 2.0
- [ ] Donations for "Cause"
- [ ] User pages
   * Items: member since, photo, subscription end date
- [ ] Badges (see Khan Academy for examples)
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
