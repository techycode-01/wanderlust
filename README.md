```markdown
# Wanderlust

A Node.js & Express-based web app inspired by Airbnb, allowing users to explore, list, and review unique stays worldwide.

## Features
- User authentication (signup, login, logout)
- Browse listings by categories: Trending, Rooms, Iconic Cities, Mountains, Castles, and more
- Add, edit, and delete listings with images (Cloudinary integration)
- Leave reviews on listings
- Session management with MongoDB
- Responsive UI with EJS templating

## Tech Stack
- Node.js, Express.js
- MongoDB Atlas with Mongoose
- Passport.js for authentication
- Cloudinary for image uploads
- EJS for views
- Multer for file uploads
- Connect-flash for notifications

## Installation
1. Clone the repo:
```

git clone [https://github.com/techycode-01/wanderlust.git](https://github.com/techycode-01/wanderlust.git)

```
2. Install dependencies:
```

npm install

```
3. Setup `.env` file with:
```

ATLASDB\_URL=<Your MongoDB Atlas URI>
SECRET=<Your Session Secret>
CLOUDINARY\_CLOUD\_NAME=<Cloudinary Cloud Name>
CLOUDINARY\_API\_KEY=<Cloudinary API Key>
CLOUDINARY\_API\_SECRET=<Cloudinary API Secret>

```
4. Run the server:
```

npm start

```
5. Visit `http://localhost:8080`

## Usage
- Explore various stays and destinations.
- Sign up and log in to add your own listings and reviews.
- Manage your listings via profile.

## Folder Structure
- `/controllers` - Request handlers
- `/models` - Mongoose schemas
- `/routes` - Express routes
- `/views` - EJS templates
- `/public` - Static assets
- `/utils` - Utility functions & error handling

## License
MIT License
```
