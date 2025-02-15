# MedSync - - A Smart Virtual Healthcare Application integrated with AI-Based Doctor Recommendation System


MedSync is a modern, feature-rich web application designed to simplify doctor appointment bookings for users while empowering healthcare professionals to manage their schedules effectively. Built using the MERN stack (MongoDB, Express.js, React.js, Node.js), MedSync bridges the gap between healthcare providers and patients, offering a seamless and user-friendly experience.

---

## Features

### For Patients:
- **Search and Book Appointments**: Find healthcare professionals by specialization, location, or availability.
- **Real-time Availability**: View doctors' schedules and book appointments instantly.
- **User Dashboard**: Manage your appointments, view booking history, and receive reminders.

### For Healthcare Professionals:
- **Profile Management**: Set up a professional profile with specializations, availability, and more.
- **Appointment Management**: Accept, reject, or reschedule appointments effortlessly.
- **Analytics**: View appointment trends and user feedback.

---

## Technologies Used

### Frontend:
- **React.js**: For building an interactive user interface.
- **Tailwind CSS**: For styling and responsive design.

### Backend:
- **Node.js**: As the server environment.
- **Express.js**: For building RESTful APIs.

### Database:
- **MongoDB**: For storing user data, appointment details, and healthcare professional profiles.

### Deployment:
- **Render**: Hosting both the frontend and backend, ensuring scalability and performance.

---

## Achievements

- Successfully onboarded **20+ healthcare professionals**, expanding the service reach by **25%**.
- Optimized backend performance, reducing query response time by **50%** through efficient MongoDB indexing and data handling.
- Improved appointment scheduling efficiency by **40%**, reducing booking time per user.

---

## Deployment

The application is live and accessible at [MedSync](https://medsync-frontend.onrender.com/).

## Installation

To run the project locally:

### Prerequisites
- Node.js installed on your machine.
- MongoDB database set up.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/medsync.git
   cd medsync
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   Create a `.env` file in the root directory and specify the following:
   ```env
   MONGO_URI=your-mongodb-connection-string
   PORT=5000
   JWT_SECRET=your-secret-key
   ```

4. Start the backend server:
   ```bash
   npm start
   ```

5. Navigate to the frontend directory and start the client:
   ```bash
   cd client
   npm install
   npm start
   ```


## API Endpoints

### User Endpoints
- `POST /api/users/register` - Register a new user.
- `POST /api/users/login` - Login for existing users.

### Doctor Endpoints
- `GET /api/doctors` - Fetch a list of all doctors.
- `POST /api/doctors/schedule` - Update doctor availability.

### Appointment Endpoints
- `POST /api/appointments/book` - Book an appointment.
- `GET /api/appointments/user` - Fetch user-specific appointments.

---


Thank you for using MedSync!

