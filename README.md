# YelpCamp

**Live Project:** [https://yelpcamp-gcxu.onrender.com/](https://yelpcamp-gcxu.onrender.com/)

YelpCamp is a web application that allows users to discover, review, and share campgrounds from around the world. Users can register, log in, add new campgrounds, leave comments, view detailed information, and see campground locations on interactive maps.

## Features

- User authentication (register/login/logout)
- Add, edit, and delete campgrounds
- Add and manage comments on campgrounds
- Responsive design for mobile and desktop
- View campground locations on an interactive MapTiler map
- Integrated MapTiler for real-time maps and location display
- Deployed and accessible online

## Technologies Used

- Node.js
- Express.js
- MongoDB & Mongoose
- Passport.js (for authentication)
- EJS (templating engine)
- Bootstrap (for styling)
- Cloudinary & Multer (for image uploads) *(if applicable)*
- MapTiler (for maps integration)

## Getting Started

### Prerequisites

- Node.js installed
- MongoDB database (local or cloud)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/yelpcamp.git
    cd yelpcamp
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and add your environment variables:
    ```
    DATABASE_URL=your_mongo_connection_string
    SECRET=your_session_secret
    CLOUDINARY_CLOUD_NAME=your_cloudinary_name
    CLOUDINARY_KEY=your_cloudinary_key
    CLOUDINARY_SECRET=your_cloudinary_secret
    MAPTILER_API_KEY=your_maptiler_api_key
    ```

4. Start the server:
    ```bash
    node app.js
    ```

5. Visit `http://localhost:3000` in your browser.

## Usage

- Register for a new account or log in
- Browse campgrounds or add your own
- View campground locations on an interactive map
- Leave comments and reviews on campgrounds

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---