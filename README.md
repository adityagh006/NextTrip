# 🏨 TripNest – Hotel Booking Platform

**TripNest** is a modern hotel booking web app built with **Next.js 14**, **TypeScript**, **Tailwind CSS**, and **Shadcn UI**. It provides a sleek, responsive interface for searching and browsing hotels, complete with loading states, search filters, and real-time hotel data integration.

## ✨ Features

- ⚡ **Next.js 14 (Server + Client Components)** – optimized rendering for performance
- 🏨 **Hotel Search & Results Pages** – browse accommodations with real-time data
- 🎨 **Modern UI/UX** – built using **Shadcn/UI** + **Tailwind CSS**
- 📱 **Fully Responsive** – works seamlessly on mobile, tablet, and desktop
- ⏳ **Skeleton Loading States** – smooth UX while fetching data
- 💻 **TypeScript** – type safety for cleaner, bug-free code

## 🛠 Tech Stack

- **Framework:** Next.js 14
- **Language:** TypeScript
- **UI Library:** Shadcn UI
- **Styling:** Tailwind CSS

## 📂 Project Structure
```
├── app/                 # Next.js app directory (routes, layouts, pages)
├── components/          # Reusable UI components
├── data/                # Static/seed data (mock data, configs)
├── lib/                 # Utility functions & helpers
├── public/              # Static assets
├── typings.ts           # Global TypeScript types
├── .env.example         # Environment variable template
├── next.config.js       # Next.js configuration
├── tailwind.config.js   # Tailwind configuration
├── tsconfig.json        # TypeScript configuration
└── README.md
```

## ⚙️ Getting Started

### 1. **Clone the repository**
```bash
git clone https://github.com/adityagh006/NextTrip.git
cd tripnest
```

### 2. **Install dependencies**
```bash
npm install
```

### 3. **Setup environment variables**
Create a `.env.local` file and configure it based on `.env.example`.

### 4. **Run the development server**
```bash
npm run dev
```

Now visit 👉 [http://localhost:3000](http://localhost:3000)

### 5. **Build for production**
```bash
npm run build
npm start
```

## 📜 License

This project is licensed under the **MIT License**.
