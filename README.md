# Winstagram

Winstagram is a full stack CRUD application that allows users to add and share pictures and posts with others through the application.

## Screenshots

![Winstagram: User Show Page](https://i.imgur.com/UWjlifR.png "Winstagram: User Show Page")

![Winstagram: User Edit Page](https://i.imgur.com/wVRu1hp.png "Winstagram: User Edit Page")

![Winstagram: Adding Comments to Posts](https://i.imgur.com/dVM6LB8.png "Winstagram: Adding Comments to Posts")

![Winstagram: Adding Posts per User](https://i.imgur.com/LI3acff.png "Winstagram: Adding Posts per User")

![Winstagram: Creating New User](https://i.imgur.com/pQDrHit.png "Winstagram: Creating New User")

## Technologies Used

- JavaScript, Node.js, Express, MongoDB, Mongoose, CSS, HTML.

## Getting Started

- Link to Winstagram app: [Winstagram](https://winstagram-build.onrender.com/)

## User Experience

- Users can create a new user account by filling out a form (accessed by "Log in to See Your Posts" link in header) that asks for their:
    - Username
    - Email address
    - Password
    - Full Name
    - Profile picture (url)
    - Brief bio
- With a created user account, users can then log in and log out of their account (user authentication and authorization).
- After logging in to their account, users can:
    - Make posts by adding pictures with optional captions to their own account
    - Make comments on their own posts/pictures or other users' posts/pictures
    - Edit or delete posts or comments that the user created
- Logged in users are able to edit their own account information, including changing their password.
- Passwords include salting and hashing process for security.
- Site includes a header with links to:
    - Homepage (includes a search bar to search user pages by username)
    - All Users (view all the users)
    - Log in to See Your Posts (log in page)
- Only after logging in, the header will then remove the "Log in to See Your Posts" link and will then show links to:
    - Your Profile (view the logged in user's show page)
    - Log Out (logs the current user out and automatically sends to log in page)

## Important Features

- 3 models and databases, each with full CRUD ability, that interact and reference each other
    - Users
    - Posts
    - Comments
- User authorization and authentication
- CSS styling
- Deployed via Render

## Next Steps/Future Considerations

- Allow users to:
    - "Like" their own or others' posts
    - Message other users
    - Add other users as friends, which could allow limited access to specific posts or user information.
    - Post videos to their users account
