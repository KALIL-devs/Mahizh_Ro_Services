# Mahizh RO Innovation

A modern, high-performance web application for Mahizh RO Innovation, a premier provider of commercial RO plants and water purification solutions in Theni. Built to showcase industrial water purification products, hospital and hotel RO solutions, and maintenance services.

![Next.js](https://img.shields.io/badge/Next.js-14+-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-19-blue?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)

## 🌟 Features

- **Modern UI/UX**: Aesthetic and responsive design built with standard CSS modules and Framer Motion for smooth, interactive animations.
- **Service & Product Showcase**: Detailed sections highlighting commercial RO plants, specialized industry solutions, and maintenance services.
- **Dynamic Routing**: Built on Next.js App Router for optimal performance, nested layouts, and server-side rendering.
- **Fast Performance**: Optimized font loading via `next/font`, image optimization, and static generation where applicable.
- **Contact Forms**: Integrated inquiry flows built with React Hook Form.

## 🛠️ Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (App Router)
- **Library**: [React](https://react.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: CSS Modules
- **Animations**: [Framer Motion](https://www.framer.com/motion/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Forms**: [React Hook Form](https://react-hook-form.com/)
- **Components**: Custom UI components including React Fast Marquee for continuous scrolling features.

## 📁 Project Structure

```text
ro_mahizh/
├── src/
│   ├── app/           # Next.js App Router (pages, layouts, globals)
│   │   ├── about/     # About Us page
│   │   ├── contact/   # Contact page
│   │   ├── industries/# Industries served
│   │   └── services/  # Services pages
│   ├── components/    # Reusable React components
│   │   ├── Home/      # Landing page components (Hero, Services, Testimonials, etc.)
│   │   ├── layout/    # Navbar, Footer, etc.
│   │   ├── marquee/   # Marquee components
│   │   ├── services/  # Service-specific components
│   │   └── ui/        # Global UI elements
│   ├── hooks/         # Custom React hooks
│   ├── lib/           # Utility functions and shared logic
│   └── types/         # TypeScript interfaces and type definitions
├── public/            # Static assets (images, icons, etc.)
└── ...config files    # Next.js, ESLint, TypeScript configurations
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18.17 or later
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ro_mahizh.git
   cd ro_mahizh
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result. You can start editing the page by modifying `src/app/page.tsx`. The page auto-updates as you edit the file.

## 🔧 Building for Production

To create an optimized production build:

```bash
npm run build
# or
yarn build
```

Then, start the production server:

```bash
npm run start
# or
yarn start
```

## 🌐 SEO & Performance

This project is configured with built-in SEO optimizations in Next.js, including dynamically generated `<title>` and `<meta>` tags in `layout.tsx` for optimal search engine visibility related to commercial RO plants in Theni.
