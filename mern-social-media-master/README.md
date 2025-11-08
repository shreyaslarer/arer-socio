

# Arer Socio - Social Media App



Arer Socio is a fullstack responsive MERN social media app with authentication, likes, dark mode, and more. Built using React, MongoDB, Express, Node.js, and Material UI.

---

## Project Structure

```
mern-social-media-master/
	client/      # React frontend
		src/
		public/
		package.json
		...
	server/      # Node.js/Express backend
		controllers/
		models/
		routes/
		public/assets/  # Uploaded images
		package.json
		...
	README.md
```

---

---


## Features
- User authentication (register/login)
- Create, like, and view posts
- Add/remove friends
- Responsive design with dark mode
- Profile and feed pages


## Tech Stack
- React, Redux Toolkit, Material UI (frontend)
- Node.js, Express, MongoDB, Mongoose (backend)

---

## Getting Started

### Prerequisites
- Node.js (v16 or above recommended)
- npm or yarn
- MongoDB (local or Atlas)

### Installation
1. **Clone the repository:**
	 ```sh
	 git clone https://github.com/shreyaslarer/arer-socio.git
	 cd arer-socio/mern-social-media-master
	 ```
2. **Install dependencies:**
	 - For the backend:
		 ```sh
		 cd server
		 npm install
		 ```
	 - For the frontend:
		 ```sh
		 cd ../client
		 npm install
		 ```

3. **Set up environment variables:**
	 - In `server/`, create a `.env` file with:
		 ```env
		 MONGO_URL=your_mongodb_connection_string
		 JWT_SECRET=your_jwt_secret
		 PORT=6001
		 ```

4. **Start the servers:**
	 - Backend:
		 ```sh
		 cd server
		 npm start
		 ```
	 - Frontend (in a new terminal):
		 ```sh
		 cd client
		 npm start
		 ```

5. **Open the app:**
	 - Visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## Usage
- Register a new user or log in with existing credentials.
- Create posts, like posts, and add/remove friends.
- Switch between light and dark mode.
- View your profile and friends list.

---

---


---
**Maintainer:** Shreyas L. ([GitHub](https://github.com/shreyaslarer))
