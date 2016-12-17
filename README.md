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
Note: Time estimates for each feature also include styling - so that when a feature is completed, it is fully styled, and completely bug-free and deployable. Estimates do not include time for research, debugging, etc.

### Phase 1: Design / UI / Hosting / Backend Setup and Front End User Authentication
####(13 hours, 01/31/17, 11:59pm)

**Objective:**
- Hosting on Heroku (.5 hours)
- Register domain, configure DNS settings, email redirect (.5 hours)
- Register account with CDN, upload sample videos for testing (.5 hours)
- General site-wide styling / UI / CSS (7 hours)
- Initial set up / CDN / Github / front and back end secure authentication (2 hours)
- Rails back-end (database, tables, API) (2 hours)
- Component to display user terms and conditions (.5 hours)

### Phase 2: Landing Page / Navigation Bar / Footer
####(3.5 hours, 01/31/17, 11:59pm)

**Objective:**
- Landing Page (2 hours)
  - Description, photos, sample videos, testimonials, etc
- Navigation Bar (.5 hours)
- Footer and Info Pages (1 hour)
  - About
  - Contact (form)
  - FAQ
  - Social media links

### Phase 3: Videos Model, API, and Components
####(3 hours, 01/31/17, 11:59pm)

**Objective:**
- Video Index (3 hours)

### Phase 3: Video Player
####(4 hours, 01/31/17, 11:59pm)

**Objective:**
- Video Player (4 hours)

### Phase 4: Cause Info
####(2 hours, 01/31/17, 11:59pm)

**Objective:**
- About Page (1 hour)
- Contact Form (1 hour)

### Total Billable Hours: 25.5

### 1.0
- [ ] Sign-up mailer
- [ ] News feed / possible Facebook integration
- [ ] Subscriptions / Payment
- [ ] Coach Forum
- [ ] Private webinars / scheduling
- [ ] Video Upload / Form / Video automatically populates to selected "section" (2 hours)

### 2.0
- [ ] Donations for "Cause"
- [ ] User pages
   * Items: member since, photo, subscription end date
- [ ] Badges (see Khan Academy for examples)
- [ ] Payment processing (Stripe or PayPal?)
   * Evaluate cost and benefits of Stripe vs. PayPal vs. other
   * Look into Koudoku gem for subscription handling
- [ ] User access to a Coaches portal page to schedule private webinars for coaching lessons / comments

### Ideas for future expansion:
  * Video tags
  * Video comments
  * Mailing list
  * Blog
  * Khan Academy-like badges, ranking, etc.

### Notes:
 * Could be helpful to have testimonials, inspirational quotes, bio, social media presence
 * Primary technical challenges: news feed / upvotes, payment processing, subscription service, video play, modals
 * Find examples of good sports-related styling / fonts / color preferences
 * Learn to use React modal for video and forms
