
# MERN Based Blog Site

This project is a full-stack blog application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to create, view, edit, and delete blog posts, along with features like user authentication, commenting, and image uploads.


## Project Structure

Mern-blog/  
├── backend/  # Backend server-side code  
│   ├── controllers/  # Controllers for API endpoints  
│   ├── models/  # Mongoose data models  
│   ├── routes/  # API routing  
│   ├── server.js  # Main server entry point  
│   └── utils/  # Utility functions  
├── client/  # Frontend client-side code  
│   ├── components/  # Reusable React components  
│   ├── pages/  # React application pages  
│   ├── services/  # Services for API interactions  
│   ├── styles/  # Global and component-specific styles  
│   ├── App.js  # Main React application component  
│   └── index.js  # Client-side entry point  
├── .env  # Environment variables for sensitive data  
├── package.json  # Project dependencies  
└── README.md  # This file (you're here!)  
## Installation

1.Clone this repository.  
2.Install dependencies:

Install my-project with npm

```bash
  npm install Blog-Mern
  cd Blog-Mern
```
    
## Configuration

Create a .env file in the project root directory and fill in the following details  
MONGODB_URI=your_mongodb_connection_string  
## Run Locally

Clone the project

```bash
  git clone https://github.com/vamsi-31/Blog-Mern
```

Go to the project directory

```bash
  cd Blog-Mern
```

Install dependencies

```bash
  npm install
```

Start Frontend


```bash
  npm run start
```
Start the server

```bash
  Node server
```
## Features

User Authentication (Registration, Login, Logout) with JWTs  
Blog Post Creation, Viewing, Editing, and Deletion  
User-based Post Ownership and Permissions  
Commenting on Blog Posts (with user information)  

## Further Resources

Mongoose: https://mongoosejs.com/docs/  
Express.js: https://expressjs.com/  
React.js: https://react.dev/  
Node.js: https://nodejs.org/en   
## License

[MIT](https://choosealicense.com/licenses/mit/)

## Contributing

Contributions are highly valued! If you have ideas for new features, bug fixes, or enhancements, please feel free to submit a pull request.
License
This project is licensed under the MIT License.
Known Issues and Limitations
Mobile Device Compatibility: The application may not be fully functional on mobile devices due to limitations in touch input and screen size.
Performance on Large Canvases: Performance may be impacted when working with very large canvases.

## Additional Notes
For optimal performance, it is recommended to use the application on a desktop or laptop computer.
If you encounter any issues or have any questions, please feel free to create an issue on the GitHub repository.


