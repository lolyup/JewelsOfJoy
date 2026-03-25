


# JewelsOfJoy E-commerce Platform

A full-stack e-commerce application featuring a handcrafted jewelry collection and a specialized beauty care line. The platform includes a real-time customer interface and a dedicated administrative dashboard for inventory management.

## Features

### Customer Interface
  * **Real-time Product Sync:** Utilizes Firebase Firestore `onSnapshot` for immediate UI updates when products are added or modified.
  * **Category Filtering:** Dynamic sorting for necklaces, rings, earrings, and bracelets.
  * **Shopping Cart System:** Persistent local storage for cart items with a slide-out sidebar for checkout management.
  * **Multi-Channel Contact:** Integrated WhatsApp and direct call buttons for customer inquiries.
  * **Responsive Design:** Optimized layouts for mobile, tablet, and desktop viewing.
  https://github.com/user-attachments/assets/50767ead-b043-43b6-ac7a-3c03b3288494
  https://github.com/user-attachments/assets/070e7dfd-e86f-4609-ac6c-f6d3d5e4e16e

### Administrative Panel
  https://github.com/user-attachments/assets/0bfea9c8-dac5-49e2-aa79-922a93abcaa3
  * **Secure Authentication:** Protected login system using Firebase Auth.
  * **Product Management:** Full CRUD (Create, Read, Update, Delete) functionality for jewelry and beauty care items.
  * **Image Management:** Integrated Cloudinary upload flow to handle high-resolution product imagery.
  * **Inventory Statistics:** Dashboard highlights for total products, featured items, and current availability status.

## Tech Stack & Architecture

The application is built on a serverless, zero-cost architecture designed for 24/7 availability without hosting overhead.

  * **Frontend:** HTML5, CSS3, JavaScript (ES6+).
  * **Database (Firestore):** A NoSQL document database storing product metadata and availability status.
  * **Authentication (Firebase Auth):** Secure administrative access control.
  * **Image Hosting (Cloudinary):** Utilized as a specialized media provider to bypass standard storage costs, providing efficient delivery of product assets.
  * **Hosting:** Served via Firebase Hosting with an automated global CDN.

## Cost Optimization

This project is engineered to run entirely on free-tier services. By offloading image storage to Cloudinary and utilizing Firebase’s serverless hosting and database tiers, the platform remains fully functional and accessible 24/7 with zero operational costs.

## Configuration

The project is initialized via `firebase-config.js`, which centralizes the API keys and service initializations (`auth`, `db`, `analytics`). Image assets are managed via Cloudinary URLs stored within the Firestore documents.

## View it live here

[https://akifjewelry.web.app](https://www.google.com/search?q=https://akifjewelry.web.app)
