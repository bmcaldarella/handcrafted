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
auth.config.ts
