# E-Commerce Platform with Next.js and GraphCMS

This project is a modern e-commerce web application built using [Next.js](https://nextjs.org/), [GraphCMS](https://graphcms.com/), and [Chakra UI](https://chakra-ui.com/). It provides a seamless shopping experience with dynamic product pages, a fully functional shopping cart, and secure payment integration.

## Key Features

### 1. **Dynamic Product Pages**

- Each product has its own dynamically generated page.
- Product data is fetched from GraphCMS using GraphQL queries.
- Example: View product details, pricing, and images.

### 2. **Shopping Cart**

- Add, update, or remove items from the cart.
- Cart state is managed using React Context for a smooth user experience.

### 3. **Secure Checkout**

- Integrated with [Stripe](https://stripe.com/) for secure payment processing.
- Users can complete their purchases with confidence.

### 4. **Responsive Design**

- Built with Chakra UI for a mobile-first, responsive design.
- Ensures a consistent experience across devices.

### 5. **Server-Side Rendering (SSR)**

- Optimized for SEO and performance using Next.js server-side rendering capabilities.

## How It Works

1. **Product Management**: Products are managed in GraphCMS, a headless CMS that allows for easy content updates.
2. **Dynamic Routing**: Next.js dynamically generates product pages based on the `slug` parameter.
3. **GraphQL Integration**: GraphQL queries fetch product data from GraphCMS.
4. **Payment Processing**: Stripe handles payment transactions securely.

## Tech Stack

- **Frontend**: Next.js, React, Chakra UI
- **Backend**: GraphCMS (Headless CMS), GraphQL
- **Payments**: Stripe
- **Styling**: CSS Modules, Chakra UI
- **State Management**: React Context API

## Project Structure

├── app/ │ ├── layout.js # Application layout │ ├── page.js # Homepage │ ├── api/ # API routes │ │ └── checkout/route.js # Checkout API integration with Stripe │ └── product/[slug]/ # Dynamic product pages ├── components/ # Reusable UI components ├── elements/ # Page-specific components │ ├── Navbar.js # Navigation bar │ ├── ProductCard.js # Product card component │ ├── ProductGrid.js # Product grid layout │ └── ProductPageTemplate.js # Product detail page template ├── lib/ # Utility libraries │ ├── context/ # React context (e.g., CartContext) │ ├── graphql/ # GraphQL queries and mutations │ └── stripe/ # Stripe integration ├── public/ # Static assets ├── styles/ # Global styles └── .env.local # Environment variables

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/ecommerce-graphcms.git
   cd ecommerce-graphcms
   ```

2. Install dependencies

   ```npm install

   ```

3. Configure environment variables: Create a .env.local file in the root directory and add:
   ```
       NEXT_PUBLIC_GRAPHQL_ENDPOINT=<your-graphql-endpoint>
       STRIPE_SECRET_KEY=<your-stripe-secret-key>
   ```
4. Start the devlopment server:

```
npm run dev
```

The application will be available at http://localhost:3000.

## Why This Project?

This project demonstrates my ability to build a full-stack e-commerce application using modern web technologies. It showcases my skills in:

- Frontend development with React and Next.js.
- Backend integration with GraphQL and headless CMS.
- Payment gateway integration with Stripe.
- Responsive design and user experience optimization.
