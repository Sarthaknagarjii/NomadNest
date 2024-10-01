# NomadNest

NomadNest is an innovative accommodation booking platform designed to provide a seamless and user-friendly experience for travelers. Inspired by platforms like Airbnb, it allows users to search, book, and manage short-term and long-term stays. The platform provides property owners with tools to list and manage accommodations, while offering travelers a smooth and intuitive interface for booking.


## Project Overview

NomadNest is designed for individuals seeking an easy way to book accommodations. Property owners can manage listings with features like adding property details, uploading images, and updating availability. Renters can browse properties, filter by location, and secure their stays through integrated payment gateways.

## Key Features

- **User Authentication & Authorization:** Secure sign-up, login, and JWT-based sessions.
- **Property Listings:** Dynamic property listings with filters for easy browsing.
- **Booking System:** Renters can book accommodations, and owners can manage availability and booking statuses.
- **Review and Rating:** Renters can leave reviews and ratings for properties.
- **Payment Integration:** Secure transactions through Stripe and PayPal for booking stays.

## Technologies Used

### Frontend

- **React.js**: Component-based structure for a dynamic and interactive UI.
- **Material-UI (MUI)**: Pre-built UI components for sleek and responsive design.
- **Next.js**: Server-side rendering (SSR) for improved performance and SEO.
  
### Backend

- **Node.js**: Server-side logic and API handling.
- **Express.js**: RESTful APIs for the backend services.
- **JWT (JSON Web Token)**: For secure user authentication and session management.
- **MongoDB**: NoSQL database for storing user, property, and booking data.


## Project Structure


## Installation

### Prerequisites

- **Node.js** (v14 or higher)
- **MongoDB**: Either a local instance or a MongoDB Atlas cloud database.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/sarthaknagarjii/nomadnest

   cd nomadnest
cd server
npm install

cd ../client
npm install


MONGO_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>
STRIPE_SECRET_KEY=<your-stripe-secret-key>


cd server
npm run dev


cd ../client
npm run dev

