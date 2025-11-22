User
- id (UUID)
- name
- email
- password
- created_at
- updated_at

Post
- id
- user_id (FK)
- title
- content
- created_at

Comment
- id
- post_id (FK)
- user_id (FK)
- message
- created_at
