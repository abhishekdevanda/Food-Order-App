# 🍽️ Food Delivery App

This is a full-stack **MERN (MongoDB, Express, React, Node.js)** food delivery application. It allows users to browse restaurants and their menus, add items to a cart, and place orders. The app features user authentication, restaurant management, and secure payment integration via Stripe.

Check out the live version: [Food Delivery App](https://food-order-app-0gjk.onrender.com)

## 🚀 Features

- User authentication (Login/Signup)
- Search restaurnats and cuisines
- Place orders and process payments
- User profile for managing orders, Profile and Address
- Responsive design for all devices
- Switch between light and dark theme
- Add your restaurant and become admin to manage your restaurant
- Admin dashboard to manage restaurants, menus, and orders

## 💻 Tech Stack

- **Frontend**: React, TailwindCSS, Shadcn UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: JWT (JSON Web Token)
- **Payment Gateway**: Stripe API
- **Images**: Cloudinary

## 📦 Dependencies

### Backend:
- [Express](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js
- [Mongoose](https://mongoosejs.com/) - Elegant MongoDB object modeling for Node.js
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) - Used for authenticating users with JWT
- [bcryptjs](https://www.npmjs.com/package/bcryptjs) - For hashing passwords
- [Stripe](https://www.npmjs.com/package/stripe) - Payment gateway integration
- [cors](https://www.npmjs.com/package/cors) - Middleware to enable Cross-Origin Resource Sharing
- [dotenv](https://www.npmjs.com/package/dotenv) - To manage environment variables
- [cloudinary](https://www.npmjs.com/package/cloudinary) - Cloud image storage
- [cookie-parser](https://www.npmjs.com/package/cookie-parser) - For parsing cookies
- [nodemailer](https://www.npmjs.com/package/nodemailer) - For sending emails
- [nodemon](https://www.npmjs.com/package/nodemon) - For automatically restarting the server when code changes

### Frontend:
- [React](https://reactjs.org/) - Frontend JavaScript library
- [TailwindCSS](https://tailwindcss.com/) - Utility-first CSS framework for styling
- [Shadcn UI](https://ui.shadcn.com/) - UI primitives for building high-quality user interfaces
- [React Router](https://reactrouter.com/) - Declarative routing for React
- [Axios](https://axios-http.com/) - Promise-based HTTP client for the browser and Node.js
- [React-Stripe](https://www.npmjs.com/package/@stripe/react-stripe-js) - For integrating Stripe in React
- [Lucide-Icons](https://lucide.dev/) - For Icons
## 🛠️ Installation and Setup

### Prerequisites:
- [Node.js](https://nodejs.org/en/download/) (v20 or later)
- [MongoDB](https://www.mongodb.com/try/download/community)
- [Stripe API Key](https://stripe.com/docs/keys)

### Steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Abhishek-Devanda/Food-Order-App.git
   cd ecommerce-store```
   ```
2. **Install backend dependencies**:
   ```bash
   npm install
   ```
3. Set up environment variables: Create a ```.env``` file in the ```backend``` folder and add the following:
   ```makefile
   PORT=5000
   BRAND_NAME=TomatoEats
   CLIENT_URL=Yours_Client_URL
   NODE_ENV=development

   #TOKENS
   OTP_EXPIRES_IN=2 * 60 * 60 * 1000
   PASSWORD_RESET_LINK_EXPIRES_IN=10 * 60 * 1000
   TOKEN_SECRET=Your_Token_Secret
   REFRESH_TOKEN_EXPIRS_IN=7d
   ACCESS_TOKEN_EXPIRS_IN=15m
   REFRESH_TOKEN_COOKIE_MAXAGE=7 * 24 * 60 * 60 * 1000
   ACCESS_TOKEN_COOKIE_MAXAGE=15 * 60 * 1000

   #MONGODB
   MONGO_URI=Your_MONGO_URI

   #CLOUDINARY
   CLOUDINARY_CLOUD_NAME =Your_CLOUDINARY_CLOUD_NAME
   CLOUDINARY_API_KEY =Your_CLOUDINARY_API_KEY
   CLOUDINARY_API_SECRET =Your_CLOUDINARY_API_SECRET

   #STRIPE
   STRIPE_PUBLISHABLE_KEY =Your_STRIPE_PUBLISHABLE_KEY
   STRIPE_SECRET_KEY =Your_STRIPE_SECRET_KEY

   #EMAIL
   SMTP_HOST =smtp.google.com
   SMTP_PASSWORD =Your_SMTP_PASSWORD
   SMTP_EMAIL =Your_SMTP_EMAIL
   ```
4. Start the backend server:
   ```bash
   npm run dev
   ```
5. Install frontend dependencies:
   ```bash
   cd frontend
   npm install
   ```
7. Start the frontend server:
   ```bash
   npm run dev
   ```
## 👏 Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request.
