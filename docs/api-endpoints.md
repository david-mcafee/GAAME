# API Endpoints

## HTML API

### Root

- `GET /` - loads React web app

## JSON API

### Users

- `POST /api/users`
- `PATCH /api/users`

### Session

- `POST /api/session`
- `DELETE /api/session`
- `GET /api/session`

### Videos

- `GET /api/videos`
- `POST /api/videos`
- `GET /api/videos/:id`
- `PATCH /api/videos/:id`
- `DELETE /api/videos/:id`

### Posts

- `GET /api/posts`
- `POST /api/posts`
- `GET /api/posts/:id`
- `PATCH /api/posts/:id`
- `DELETE /api/posts/:id`

### Upvotes

- `GET /api/posts/:post_id/upvotes`
- `POST /api/posts/:post_id/upvotes`
- `PATCH /api/posts/:post_id/upvotes/upvotes_id`
- `DELETE /api/posts/:post_id/upvotes/upvotes_id`

### Comments

- `GET /api/posts/:post_id/comments`
- `POST /api/posts/:post_id/comments`
- `PATCH /api/posts/:post_id/comments/:comment_id`
- `DELETE /api/posts/:post_id/comments/:comment_id`
