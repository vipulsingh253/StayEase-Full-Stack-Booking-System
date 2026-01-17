# StayEase - Full Stack MERN Project

A high-performance, full-stack **Airbnb Clone** built using the MERN stack. This application features a robust property listing system, secure user authentication, real-time booking, and a dynamic search engine.

##  Live Demo
[Insert Your Render/Deployment Link Here]

##  Key Features
* **Secure Authentication:** User sign-up, login, and logout functionality using **JWT (JSON Web Tokens)** and HTTP-only cookies for enhanced security.
* **Property Management (CRUD):** Complete Create, Read, Update, and Delete operations for property listings, including price and detail management.
* **Advanced Image Handling:** Integrated **Multer** for local file processing and **Cloudinary** for secure, cloud-based image storage.
* **Smart Booking System:** Real-time booking logic that prevents double-booking and calculates total stay costs (including taxes/fees) dynamically.
* **Interactive Search:** Filter properties by title, city, or landmark using a backend-optimized search query.
* **User Rating System:** Allows guests to provide star-based feedback on their stays, which updates the property's global rating.
* **Responsive UI:** A mobile-first design approach using **Tailwind CSS** to ensure a seamless experience across all devices.

##  Tech Stack
* **Frontend:** React.js, Tailwind CSS, React Router Dom, Axios, React Toastify (Notifications).
* **Backend:** Node.js, Express.js.
* **Database:** MongoDB Atlas with Mongoose ODM.
* **Storage:** Cloudinary API for cloud image hosting.
* **Middleware:** Multer (File uploads), JWT (Auth), Bcrypt (Password hashing).

##  Installation & Local Setup

1.CLONE THE REPOSITORY
```bash
git clone [https://github.com/vipulsingh253/airbnb-mern-clone.git](https://github.com/vipulsingh253/airbnb-mern-clone.git)
cd airbnb-mern-clone

2.CONFIGURE BACKEND
Navigate to the backend: cd backend

Install dependencies: npm install

Create a .env file and add your credentials:
PORT=8000
MONGO_DB_URL=your_mongodb_atlas_url
JWT_SECRET=your_jwt_secret_key
CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_secret

Start the server: npm run dev

3. CONFIGURE FRONTEND
Navigate to the frontend: cd ../frontend

Install dependencies: npm install

Start the application: npm run dev

4. Application Interface
Explore: Dynamic landing page with category-based filtering (Villas, Shops, Pools, etc.).

Host Mode: Dedicated "My Listings" section for users to manage their property portfolio.

Trips: "My Bookings" dashboard to track upcoming stays and provide ratings for completed trips.

5. License
This project is licensed under the MIT License - see the LICENSE file for details.
