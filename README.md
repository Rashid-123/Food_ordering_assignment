# Foodies Delivery Service

A food delivery app with location , distance and delivery time 

## 📌 Clone the Repository
```sh
git clone https://github.com/Rashid-123/Food_ordering_assignment.git
cd Food_ordering_assignment
```

## 🔧 Backend Setup
1. Navigate to the backend directory:
   ```sh
   cd mern-food-ordering-app-backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file in the backend directory and add the following:
   ```plaintext
   MONGODB_CONNECTION_STRING=your_mongodb_connection_string
   AUTH0_AUDIENCE=your_auth0_audience
   AUTH0_ISSUER_BASE_URL=your_auth0_issuer_base_url
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   FRONTEND_URL=your_frontend_url
   STRIPE_API_KEY=your_stripe_api_key
   STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
   ```
4. Start the backend server:
   ```sh
   npm run dev
   ```

## 🎨 Frontend Setup
1. Navigate to the frontend directory:
   ```sh
   cd ../mern-food-ordering-app-frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file in the frontend directory and add the following:
   ```plaintext
   VITE_API_BASE_URL=your_api_base_url
   VITE_AUTH0_DOMAIN=your_auth0_domain
   VITE_AUTH0_CLIENT_ID=your_auth0_client_id
   VITE_AUTH0_CALLBACK_URL=your_auth0_callback_url
   VITE_AUTH0_AUDIENCE=your_auth0_audience
   VITE_OPENROUTESERVICE_API_KEY=your_openrouteservice_api_key
   ```
4. Start the frontend server:
   ```sh
   npm run dev
   ```


## 🚀 Project is now running!
The backend will run on `http://localhost:7000` and the frontend on `http://localhost:5173`.





