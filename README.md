# Beautify Me – Beauty Service Booking Platform

**Beautify Me** is a full-stack beauty service booking platform that allows customers to explore available beauty services, schedule appointments, make payments, and share reviews based on their experiences.

The platform provides date and time-slot-based appointment booking, personalized user dashboards, service history, and an administrative dashboard for managing users, services, and platform activities.

## 🌐 Live Project

- **Live Website:** https://beautify-me-e67e5.web.app/
- **Live API:** https://beautify-me-server.up.railway.app/
- **Client Repository:** https://github.com/TanvirFahimBD/beautify-me-client
- **Server Repository:** https://github.com/TanvirFahimBD/beautify-me-server

---

## 📸 Project Screenshots

<!-- Add actual project screenshots to the screenshots directory -->

| Home Page | Services |
|:---:|:---:|
| ![Home Page](./screenshots/home.png) | ![Services](./screenshots/services.png) |

| User Dashboard | Admin Dashboard |
|:---:|:---:|
| ![User Dashboard](./screenshots/user-dashboard.png) | ![Admin Dashboard](./screenshots/admin-dashboard.png) |

---

## ✨ Key Features

### 👤 User Features
- User registration and login.
- Authentication required before booking services.
- Browse available beauty services.
- Book appointments by selecting a specific date and time slot.
- View and update personal profile information.
- Access a personalized user dashboard.
- Make booking payments through the dashboard.
- Submit reviews for previously received services.
- View booking and service history.

### 🛡️ Admin Features
- Access a dedicated admin dashboard.
- View and manage user accounts.
- Delete existing user accounts.
- Assign administrator roles to other users.
- Create and publish new beauty services.
- Delete existing beauty services.
- Manage users and available services.

### 🔒 Additional Features
- Firebase Authentication.
- Role-based dashboard access.
- Protected routes for authenticated users.
- Date-based appointment scheduling.
- Time-slot-based booking management.
- Custom 404 page for unknown routes.

---

## 🛠️ Technologies Used

### Frontend
- **React.js** – Building reusable UI components and interactive user interfaces.
- **React Router** – Managing client-side routing and navigation.
- **Firebase Authentication** – Handling user authentication and account management.

### Backend
- **Node.js** – Providing the server-side JavaScript runtime.
- **Express.js** – Developing REST APIs and handling backend requests.
- **MongoDB** – Storing and managing application data.

### Deployment & Hosting
- **Firebase Hosting** – Hosting the frontend application.
- **Railway** – Deploying and hosting the backend API.

---

## 📦 Dependencies

### Frontend Dependencies

Main dependencies based on the project architecture:

- react
- react-dom
- react-router-dom
- firebase

### Backend Dependencies

Main expected dependencies:

- express
- mongodb
- cors
- dotenv

> **Note:** Check both repositories' `package.json` files to include the exact dependencies and versions used in the project.

---

## ⚙️ Run Locally

Follow these steps to run the project on your local machine.

### Prerequisites

Make sure you have installed:

- Node.js (LTS recommended)
- npm
- Git
- MongoDB account or local MongoDB server
- Firebase project with Authentication configured

### 1. Clone the Frontend Repository

```bash
git clone https://github.com/TanvirFahimBD/beautify-me-client.git

cd beautify-me-client
```

### 2. Install Frontend Dependencies

```bash
npm install
```

### 3. Configure Frontend Environment Variables

Create a `.env` file in the frontend root directory.

```env
REACT_APP_API_URL=http://localhost:5000

REACT_APP_apiKey=your_firebase_api_key
REACT_APP_authDomain=your_firebase_auth_domain
REACT_APP_projectId=your_firebase_project_id
REACT_APP_storageBucket=your_firebase_storage_bucket
REACT_APP_messagingSenderId=your_firebase_sender_id
REACT_APP_appId=your_firebase_app_id
```

> Adjust the variable names according to your actual frontend configuration. If the project uses Vite, use the `VITE_` prefix instead of `REACT_APP_`.

### 4. Clone the Backend Repository

Open another terminal and clone the server repository.

```bash
git clone https://github.com/TanvirFahimBD/beautify-me-server.git

cd beautify-me-server
```

### 5. Install Backend Dependencies

```bash
npm install
```

### 6. Configure Backend Environment Variables

Create a `.env` file in the backend root directory.

```env
PORT=5000

DB_USER=your_mongodb_username
DB_PASS=your_mongodb_password
```

Add other environment variables required by the backend implementation, including payment gateway credentials if applicable.

### 7. Start the Backend Server

```bash
npm start
```

If the project has a development script, you can also use:

```bash
npm run dev
```

Backend API:

```text
http://localhost:5000
```

### 8. Start the Frontend Application

Return to the frontend terminal.

```bash
npm start
```

For Vite-based projects:

```bash
npm run dev
```

The application should now be accessible through your local development server.

---

## 🧠 Technology Choices & Why I Used Them

| Technology | Purpose |
|---|---|
| React.js | Building reusable and interactive UI components |
| React Router | Managing application navigation and protected routes |
| Firebase Authentication | Handling user registration and login |
| Node.js | Running server-side JavaScript |
| Express.js | Developing REST APIs and backend services |
| MongoDB | Managing users, services, bookings, and reviews |
| Firebase Hosting | Deploying and hosting the frontend |
| Railway | Deploying and hosting the backend API |

---

## 🚧 Challenges Faced During Development

Some important engineering challenges addressed while developing the platform:

- **Authentication & Authorization:** Implementing authentication and restricting booking functionality to logged-in users.
- **Appointment Scheduling:** Managing date-specific bookings and time-slot selection.
- **Booking Management:** Handling booking information and maintaining service history.
- **Payment Integration:** Connecting the booking workflow with payment functionality.
- **Role-Based Access Control:** Separating user and administrator permissions and dashboard functionality.
- **User Management:** Implementing administrative operations such as deleting accounts and assigning admin roles.
- **Service Management:** Implementing service creation and deletion functionality.
- **Frontend & Backend Integration:** Connecting React components with Express APIs and managing asynchronous data communication.
- **Deployment Configuration:** Deploying the frontend and backend separately and configuring their communication.

---

## 💡 Problems Solved

- Simplified the process of discovering and booking beauty services online.
- Provided date and time-slot-based appointment scheduling.
- Reduced the need for manual appointment management.
- Centralized customer booking and service history.
- Enabled customers to make payments through their dashboard.
- Introduced a review system for collecting customer feedback.
- Provided administrators with centralized user and service management.
- Established separate user and admin dashboards.

---

## 🔮 Future Improvements

- Real-time appointment availability.
- Booking cancellation and rescheduling.
- Automated booking confirmation and email notifications.
- Advanced service filtering and searching.
- Admin analytics and revenue reporting.
- Improved appointment management.
- Additional security and performance optimizations.

---

## 👨‍💻 Developer

**Tanvir Hossain Fahim**  
Software Engineer | Full-Stack Developer

- **Portfolio:** https://tanvir-fahim-bd.netlify.app/
- **GitHub:** https://github.com/TanvirFahimBD
- **LinkedIn:** https://www.linkedin.com/in/tanvir-fahim/

---

⭐ If you find this project interesting, consider giving it a star!

**Built with ❤️ to make beauty service booking easier and more convenient.**
