# Blog With Database

This is a simple blogging web application built with Node.js, Express.js, EJS templating engine, and MongoDB. It allows users to create and publish blog posts, view existing posts, and read individual posts.

## Features

- User-friendly interface for creating and publishing blog posts
- Displaying a list of published blog posts on the home page
- Read individual blog posts by clicking on the "Read More" button
- Separate pages for About and Contact information
- Integration with a MongoDB database to store and retrieve blog post data

## Installation

1. Clone the repository:

https://github.com/ehasan8115/blog-with-database.git

2. Install the dependencies:

cd blog-with-database
npm install


3. Set up the MongoDB database:

- Make sure MongoDB is installed and running on your system.
- Update the MongoDB connection URL in `app.js` to match your MongoDB configuration:

  ```javascript
  mongoose.connect("mongodb://127.0.0.1:27017/blogDB", { useNewUrlParser: true, useUnifiedTopology: true });
  ```

4. Start the server:

node app.js


5. Open your web browser and visit `http://localhost:3000` to access the application.

## Usage

- **Home Page**: Displays a list of published blog posts.
- **Compose Page**: Allows you to create and publish new blog posts.
- **Individual Post Page**: Displays the full content of a blog post.
- **About Page**: Provides information about the blog or the author.
- **Contact Page**: Allows users to contact the blog owner.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## Deployment

The project is deployed and accessible at [https://blog-with-database-3qz1.onrender.com]

