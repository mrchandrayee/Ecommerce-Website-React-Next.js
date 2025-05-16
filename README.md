# 🛒 NextCommerce | Modern Multivendor E-commerce Platform

<div align="center">
  <img src="./public/assets/icons/cart.avif" alt="NextCommerce Icon" width="150" />
  <br />
  <p>
    <strong>Comprehensive E-commerce Solution with Advanced Features</strong>
  </p>
  <p>
    <a href="#demo">View Demo</a> •
    <a href="#features">Features</a> •
    <a href="#tech-stack">Tech Stack</a> •
    <a href="#getting-started">Getting Started</a>
  </p>
</div>

---

## 📋 Overview

NextCommerce is a sophisticated, feature-rich e-commerce solution built with modern web technologies. This platform enables multiple vendors to showcase and sell their products while providing shoppers with an intuitive, responsive, and secure shopping experience.

### Key Differentiators

✅ **Full-Stack Solution** - Built with Next.js 14, TypeScript, and Prisma  
✅ **Multi-Vendor Architecture** - Support for multiple sellers with individual stores  
✅ **Advanced Product Management** - Complete with variants, specifications, and inventory  
✅ **Secure Payment Integration** - Multiple payment options with Stripe and PayPal  
✅ **Responsive Design** - Mobile-first approach for all device types  
✅ **Scalable Infrastructure** - Built for growth and high traffic volumes

---

## ✨ Features

<details open>
<summary><b>🛍️ For Shoppers</b></summary>
<br>

| Feature | Description |
|---------|-------------|
| **User Authentication** | Secure sign-in and registration via Clerk with social login options |
| **Intelligent Search** | Elasticsearch-powered product search with filters and suggestions |
| **Shopping Cart** | Real-time cart management with Zustand state management |
| **Wishlist System** | Save and organize favorite products for future purchase |
| **Multiple Payment Options** | Seamless checkout with Stripe and PayPal integration |
| **Order Tracking** | Comprehensive order history and real-time status updates |
| **Product Reviews** | Rating system with text reviews and image uploads |
| **Responsive Design** | Optimized shopping experience across all devices |

</details>

<details>
<summary><b>🏪 For Sellers</b></summary>
<br>

| Feature | Description |
|---------|-------------|
| **Store Management** | Create and customize your branded storefront |
| **Product Management** | Comprehensive tools for adding and managing products with multiple variants |
| **Inventory Control** | Real-time stock management and low-stock alerts |
| **Order Processing** | Streamlined workflow for order fulfillment |
| **Sales Analytics** | Visual dashboards for monitoring store performance |
| **Coupon System** | Create and manage promotional offers and discount codes |
| **Customer Communication** | Direct messaging with customers about orders |

</details>

<details>
<summary><b>👑 For Administrators</b></summary>
<br>

| Feature | Description |
|---------|-------------|
| **Dashboard** | Comprehensive admin interface with key metrics |
| **User Management** | Manage all user accounts with role-based permissions |
| **Store Verification** | Process for approving and monitoring seller stores |
| **Content Management** | Tools for managing categories, featured items, and promotions |
| **System Configuration** | Platform settings and payment gateway configuration |
| **Analytics & Reporting** | Site-wide analytics for data-driven decisions |

</details>

---

## 🔧 Tech Stack

<details open>
<summary><b>Frontend Technologies</b></summary>
<br>

- **React 18** - Component-based UI development
- **Next.js 14** - React framework with server-side rendering
- **TypeScript** - Type-safe code for better development
- **TailwindCSS** - Utility-first CSS framework for responsive design
- **shadcn/ui** - High-quality UI components built on Radix UI
- **Zustand** - Lightweight state management solution
- **React Hook Form** - Efficient form validation and handling
- **Framer Motion** - Animations and transitions for enhanced UX

</details>

<details>
<summary><b>Backend & Data Technologies</b></summary>
<br>

- **Next.js API Routes** - Serverless backend functionality
- **Prisma ORM** - Type-safe database access with migrations
- **MySQL** - Relational database for structured data storage
- **Elasticsearch** - Advanced search capabilities
- **Clerk Auth** - User authentication and management
- **Stripe & PayPal** - Secure payment processing
- **Cloudinary** - Cloud-based image management

</details>

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have:

- **Node.js** v18.x or later
- **MySQL** database server
- **Stripe** and **PayPal** developer accounts
- **Elasticsearch** instance
- **Cloudinary** account (for image management)
- **Clerk** account (for authentication)

### Quick Installation

<details open>
<summary><b>Step 1: Clone & Setup</b></summary>

```bash
# Clone the repository
git clone https://github.com/your-username/NextCommerce.git

# Navigate to project directory
cd Ecommerce-Website-React-Next.js

# Install dependencies
npm install
# or
bun install
```
</details>

<details>
<summary><b>Step 2: Environment Configuration</b></summary>

Create a `.env` file in the root directory with these required variables:

```env
# Database
DATABASE_URL="mysql://username:password@host:port/database"

# Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# Search
ELASTICSEARCH_NODE=your_elasticsearch_node
ELASTICSEARCH_USERNAME=your_elasticsearch_username
ELASTICSEARCH_PASSWORD=your_elasticsearch_password

# Payments
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
NEXT_PUBLIC_PAYPAL_CLIENT_ID=your_paypal_client_id

# Media
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
```
</details>

<details>
<summary><b>Step 3: Database Setup & Launch</b></summary>

```bash
# Initialize your database
npx prisma db push

# Start the development server
npm run dev
# or
bun dev

# Open http://localhost:3000 in your browser
```
</details>

---

## 📁 Project Architecture

```
NextCommerce/
├── prisma/              # Database schema and migrations
├── public/              # Static assets and images
├── src/
│   ├── app/             # App router pages and API routes
│   │   ├── (auth)/      # Authentication routes
│   │   ├── (store)/     # User-facing store routes
│   │   └── dashboard/   # Admin and seller dashboards
│   ├── components/      # Reusable UI components
│   ├── lib/             # Utility functions and types
│   ├── queries/         # Data fetching functions
│   └── providers/       # Context providers
└── types/               # Global TypeScript definitions
```

---



<div align="center">
  <p>Crafted with ❤️ by Your Team</p>
  <p>
    <a href="https://github.com/mrchandrayee">GitHub</a> •
    <a href="https://chandrayee.me">Website</a> •
    <a href="mailto:chandrayee.cset@gmail.com">Contact</a>
  </p>
</div>


