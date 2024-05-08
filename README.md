# Organic Shop

Organic Shop is a real-world e-commerce application built with Angular, Firebase, and Bootstrap 4. It provides a seamless online shopping experience for users looking for organic products. The application is designed with responsive web design principles to ensure a smooth user experience across various devices and screen sizes.

## Features

- **User Authentication**: Users can log in using Google authentication to access and manage their shopping carts.
- **Dynamic Product Listing**: Products are categorized, and users can view products under selected categories.
- **Shopping Cart**: Users can add products to their shopping cart, change quantities, and see the real-time update of the total cost.
- **Checkout Process**: A checkout feature that includes filling out shipping information. Authentication is required to access the checkout process.
- **Order Management**: After placing an order, users are redirected to an order success page displaying the order ID.
- **Admin Features**: Administrative users can manage orders and products. Features include sorting, resizing columns, pagination, and searching for specific products.
- **Responsive Design**: Built using Bootstrap 4 for a responsive layout that adjusts to different screen sizes and devices.

## Technologies Used

- **Angular**: Frontend framework for building the client-side of the application.
- **Firebase**: Backend-as-a-Service (BaaS) used for hosting, user authentication, and data storage.
- **Bootstrap 4**: Styling framework for developing responsive and mobile-first websites.
- **Firebase Functions**: (Note: This feature is mentioned but not used in the free plan of Firebase)

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone [URL to the repository]
   ```
2. **Install Dependencies**:
   ```bash
   cd organic-shop
   npm install
   ```
3. **Environment Configuration**:
   Ensure you have the Firebase configurations set in your environment files.
   ```
   src/environments/environment.ts
   ```
4. **Run the Application**:
   ```bash
   ng serve
   ```
   Navigate to `http://localhost:4200/` to view the application.

## Possible Extensions

- **Billing Integration**: Integrate payment providers like PayPal or Stripe to handle transactions.
- **Advanced Product Features**: Add filters and advanced search options to enhance product browsing.
- **Mobile App**: Extend the platform to a native mobile app using Angular Ionic for better mobile performance.
