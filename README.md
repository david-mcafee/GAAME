The layout of the platform will utilize React/Redux to create the single-page app feel, but I’d like to make sure I’m understanding the components correctly. Also, time estimates for each feature also include styling - so that when a feature is completed, it is fully styled, and completely bug-free and deployable.

Name: GAAME
join the game, get in the game

Phases:
- Initial set up / CDN / Github / general site-wide styling / front and back end secure authentication (10 hours)
- Back-end (database, tables, API) (2 hours)
- Video Index (3 hours)
- Video Player (3 hours)
- Video upload (1 hour)
- Comments (8 hours)
- Forms (3 hours)
- Do we want modals?
- Footer (30 min)

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
