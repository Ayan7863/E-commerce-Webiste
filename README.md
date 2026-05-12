# Moonlight Attar & Perfumes - Luxury E-commerce Website

A premium e-commerce website for luxury perfumes, attars, and oud fragrances built with Next.js 14, Tailwind CSS, and Framer Motion.

## 🌟 Features

### 🎨 Design & Themes
- **Dual Theme Support**: Dark (black + gold) and Light (cream + rose gold) themes
- **Luxury Design**: Premium, elegant styling with smooth animations
- **Responsive**: Optimized for mobile, tablet, and desktop

### 🛍️ E-commerce Features
- **Product Catalog**: Perfumes, Attars, Oud, and Gift Sets
- **Shopping Cart**: Add/remove items, quantity management
- **Product Filters**: Filter by type, size, price range, fragrance notes
- **Best Sellers**: Featured products with ratings and reviews
- **Special Offers**: Festive discounts and promotional banners

### 🧠 Smart Features
- **Fragrance Quiz**: Personalized recommendations based on personality and mood
- **Search & Filters**: Advanced filtering system
- **Customer Reviews**: Product ratings and feedback
- **Order Tracking**: Track your orders (coming soon)

### 💳 Payment Integration (Ready for Implementation)
- **Razorpay**: For Indian payments
- **Stripe/PayPal**: For international payments

## 🚀 Tech Stack

- **Frontend**: Next.js 14 with App Router
- **Styling**: Tailwind CSS with custom luxury theme
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Theme**: Next-themes for dark/light mode
- **TypeScript**: Full type safety
- **Database**: MongoDB Atlas with Mongoose

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ayan7863/E-commerce-Webiste.git
   cd moonlight
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env.local` file and add:
   ```
   MONGODB_URI=your_mongodb_connection_string
   NEXTAUTH_SECRET=your_secret_key
   NEXTAUTH_URL=http://localhost:3000
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🎯 Project Structure

```
moonlight/
├── app/                    # Next.js 14 App Router
│   ├── api/               # API routes (backend)
│   ├── admin/             # Admin dashboard
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Homepage
├── components/            # React components
├── lib/                   # Utility functions & DB connection
├── public/                # Static assets
└── tailwind.config.js     # Tailwind configuration
```

## 🎨 Theme Configuration

### Light Theme
- **Primary**: Cream (#F5F5DC)
- **Accent**: Rose Gold (#E8B4B8)

### Dark Theme
- **Primary**: Black (#000000)
- **Accent**: Gold (#FFD700)

## 🔧 Development Scripts

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run start    # Start production server
npm run lint     # Run ESLint
```

## 🚀 Deployment

Deployed on **Vercel** — [Live Demo](https://your-vercel-url.vercel.app)

## 📞 Business Information

- **Business Name**: Moonlight Attar & Perfumes
- **Instagram**: [@moonlight_attar_perfumes](https://instagram.com/moonlight_attar_perfumes)
- **Tagline**: "Discover your Signature Scent"

## 📄 License

This project is created for Moonlight Attar & Perfumes. All rights reserved.

---

**Built with ❤️ for luxury fragrance enthusiasts**
