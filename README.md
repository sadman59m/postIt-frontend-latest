# postIt
- A multiuser social media platform where people can share their thoughts with others.
- The main goal of this project was to practice building the front part using React and react-router, and the backend part using node.js, Express, and MongoDB. I also learned how to create APIs, design API endpoints, and connect the REST API smoothly within the project.

# Live site
Checkout live: https://post-it-frontend-latest-ek3y.vercel.app/
- Note: The backend is hosted on render.com which makes the server inactive after 15 minutes of inactivity. So for the
  first time, you are logging in, it may take up to 30s to log in as the render.com take 30s to reactivate the server.
  Once reactivated, there won't be any delay anymore.
- For Quick Login:
- email: test@test.com
- password: tester

# Features
- User authentication and authorization using JWT.
- Users can create posts, update and delete their own posts.
- Server-side input data validation.
- All the users get the latest updates through socket.io.
- REST API for every request.

# Stack Used
- Frontend: ReactJs, react-router-dom, socket.io client.
- Backend: node.js, Express, MongoDB, Mongoose, socket.io server.
