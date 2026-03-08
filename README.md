# Handcrafted Haven

Handcrafted Haven is a digital marketplace designed to connect independent artisans with customers who appreciate handmade, unique, and sustainable products. The platform focuses on giving visibility to small creators while providing a modern and intuitive shopping experience.

This project was developed using a modern full-stack JavaScript environment with a strong focus on scalability, collaboration, and clean architecture.

---

# Live Demo

https://handcrafted-haven-rouge-phi.vercel.app

---

# Project Overview

Handcrafted Haven is an e-commerce style platform where artisans can showcase their handmade products and customers can browse, explore, and purchase unique items.

The application includes product browsing, product details, seller profiles, authentication, reviews, and shopping cart functionality.

The goal of the platform is to create a marketplace that highlights the identity of each seller and allows users to discover products directly from independent creators.

---

# Collaboration

This repository is a **fork of the original project created by Simphiwe Nkabinde**.

I worked on this project **in collaboration with the repository owner**, contributing features, improvements, and integrations within the existing codebase.

Rather than building the entire platform independently, my role focused on extending functionality, improving seller-related features, and integrating product and seller data across the application.

This fork represents my **technical contributions and collaborative work** within the original project.

---

# My Contributions

My work on this project included contributions related to the seller experience and the integration between products and seller profiles.

Main areas I worked on include:

- Implementing seller information on the product detail page
- Extending the `fetchProductById` function to include seller data
- Improving the **products-by-user** functionality
- Developing and improving the **My Profile / Seller Profile** experience
- Integrating seller data with product pages
- Merging collaborative pull requests into the main branch
- Improving project structure and feature integration

These contributions helped strengthen the connection between sellers and the products displayed on the platform.

---

# Features

The application currently includes the following functionality:

- Product catalog and browsing
- Product detail pages
- Seller profile pages
- User authentication
- Product reviews
- Shopping cart system
- Category filtering
- Product pagination
- Seller product listings
- Marketplace-style navigation

---

# Tech Stack

Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS

Backend / Data Layer

- NextAuth
- PostgreSQL
- Zod
- bcrypt

Development Tools

- Node.js
- Git
- Vercel (deployment)

---

# Project Structure
app/
(auth)/
cart/
checkout/
dashboard/
inventory/
lib/
products/
profile/
profiles/
seed/
ui/

public/

auth.ts
auth.config.ts



The application follows a modular structure using Next.js app routing.  
Data fetching and server logic are organized inside the `lib` directory.

---

# Key Technical Notes

The platform connects product data with seller data so that users can easily see who is selling a product and navigate directly to the seller's profile.

Key backend functions include:

- Fetching product lists
- Fetching categories
- Retrieving product reviews
- Loading seller profiles
- Loading seller products
- Checking product ownership
- Managing shopping cart items
- Counting cart items for the user session

This structure allows the application to scale while keeping logic organized.

---

# Installation

Clone the repository:
git clone https://github.com/bmcaldarella/handcrafted.git


Move into the project folder:
cd handcrafted

Install dependencies:
npm install

Run the development server:
npm run dev

Open the browser at:
http://localhost:3000


---

# Environment Variables

The project requires environment variables for database access and authentication.

Example configuration:
POSTGRES_URL=your_postgres_connection_string
AUTH_SECRET=your_auth_secret
AUTH_URL=http://localhost:3000


Create a `.env.local` file in the root of the project and add your values there.

---

# Future Improvements

Potential improvements for the platform include:

- Completing the checkout and payment flow
- Improving the seller dashboard
- Adding order management
- Enhancing mobile responsiveness
- Adding automated tests
- Improving error handling
- Expanding marketplace features

---

# Acknowledgment

The original project was created by **Simphiwe Nkabinde**.

This repository is a fork that reflects my **collaborative contributions, feature work, and improvements** made while working within the original project.
