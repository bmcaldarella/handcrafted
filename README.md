# Handcrafted Haven

Handcrafted Haven is a digital marketplace built to connect independent artisans with customers who value handmade, unique, and sustainable products. The platform focuses on community, seller visibility, and a smoother shopping experience for handcrafted goods.

## Live Demo

https://handcrafted-haven-rouge-phi.vercel.app/

## Project Overview

This project was developed as a collaborative e-commerce platform where artisans can showcase their products, manage their seller presence, and connect with buyers through a modern web experience.

The application includes product browsing, product details, seller profiles, authentication, reviews, and cart-related functionality. It is designed to support both customers and sellers in a marketplace environment.

## Collaboration

This repository is a fork of the original project created by **Simphiwe Nkabinde**, and I contributed to the project in collaboration with the original repository owner.

My work on this project focused on improving the seller experience and strengthening the connection between products and seller identity across the platform. Rather than building the entire platform alone, I worked as a collaborator on an existing team project and contributed features, refactors, and merges that became part of the application.

## My Contributions

My visible contributions in this repository include work related to:

- Fetching and displaying seller information on the product detail page
- Adding seller information to the `fetchProductById` data layer
- Improving the **products by users** feature
- Creating and improving the **seller profile / My Profile** experience
- Merging and integrating collaborative pull requests into the main branch

These contributions helped improve how seller data is presented, how users navigate between products and seller profiles, and how seller-related features are structured in the app.

## Main Features

- Product listing and product detail pages
- Product filtering, search, and pagination
- Seller profile pages
- Current seller profile management
- User authentication and session handling
- Product reviews
- Shopping cart functionality
- Marketplace-style browsing experience

## Tech Stack

- **Next.js**
- **React**
- **TypeScript**
- **NextAuth**
- **Postgres**
- **Tailwind CSS**
- **Zod**
- **bcrypt**

## Project Structure

```bash
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
auth.config.ts``


Key Technical Notes

The application uses a Next.js app-based structure with server-side data fetching and authentication logic. The data layer includes functions for:

fetching products

fetching product categories

retrieving product reviews

loading seller profiles

loading seller products

checking product ownership

handling cart item counts and cart items

Seller data is connected to products so buyers can view who is selling an item and navigate to the seller's profile page for more context.

Installation

Clone the repository:

git clone https://github.com/bmcaldarella/handcrafted.git
cd handcrafted

Install dependencies:

npm install

Run the development server:

npm run dev

Open http://localhost:3000 in your browser.

Environment Variables

You will need environment variables for database and authentication setup. Based on the project structure, this app uses a Postgres connection and authentication configuration.

Example:

POSTGRES_URL=your_postgres_connection_string
AUTH_SECRET=your_auth_secret
AUTH_URL=http://localhost:3000

Update these values according to your local or deployed environment.

Why This Project Matters

This project helped me practice real collaboration in a shared codebase, contribute features to an existing product, and work on marketplace functionality using a modern full-stack JavaScript/TypeScript stack.

It also gave me experience contributing to a project through feature work, integration, and collaborative development rather than only building solo projects from scratch.

Future Improvements

Complete cart and checkout flows

Improve seller dashboard features

Add stronger validation and error states

Improve responsive polish across all pages

Add tests for critical flows

Expand order management features

Acknowledgment

Original project repository and initial project ownership belong to Simphiwe Nkabinde.
This fork reflects my collaborative contributions and feature work within that project.


---

## La parte más importante: cómo decir que trabajaste con el owner

Esta línea está bien y suena profesional:

```md
This repository is a fork of the original project created by **Simphiwe Nkabinde**, and I contributed to the project in collaboration with the original repository owner.

Y esta también está muy buena para portfolio:

This fork documents my collaborative contributions to the original Handcrafted Haven project.


