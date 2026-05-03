# WanderNest - Travel Website Portfolio Project

This is a portfolio project showcasing a modern travel website built with cutting-edge web technologies. WanderNest is a fictional travel agency website designed to demonstrate full-stack development skills.

## 🚀 Tech Stack

- **Frontend Framework**: React 19 with TypeScript
- **Routing**: TanStack Router (React Router successor)
- **Build Tool**: Vite
- **Styling**: Tailwind CSS v4
- **UI Components**: Radix UI primitives with custom styling
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Forms**: React Hook Form with Zod validation
- **Charts**: Recharts
- **Package Manager**: Bun
- **Deployment**: Vercel

## 🛠️ Development Setup

### Prerequisites
- Node.js 18+ or Bun
- Git

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd wander-nest
```

2. Install dependencies:
```bash
bun install
```

3. Start development server:
```bash
bun run dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production

```bash
bun run build
```

### Preview Production Build

```bash
bun run preview
```

## 📁 Project Structure

```
src/
├── components/
│   ├── site/          # Site-specific components (Navbar, Footer, UI)
│   └── ui/            # Reusable UI components (shadcn/ui)
├── data/              # Static data and content
├── hooks/             # Custom React hooks
├── lib/               # Utility functions
├── routes/            # TanStack Router route components
└── styles.css         # Global styles and Tailwind imports
```

## 🎨 Features

- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Modern Routing**: File-based routing with TanStack Router
- **Component Library**: Custom UI components built on Radix UI
- **Form Handling**: Type-safe forms with validation
- **Animations**: Smooth transitions and micro-interactions
- **SEO Optimized**: Meta tags and structured data
- **Performance**: Optimized builds with Vite

## 🚀 Deployment

This project is configured for deployment on Vercel:

1. Connect your GitHub repository to Vercel
2. Vercel will automatically detect the Vite configuration
3. The `vercel.json` file ensures proper routing for SPA

## 📝 Scripts

- `bun run dev` - Start development server
- `bun run build` - Build for production
- `bun run preview` - Preview production build
- `bun run lint` - Run ESLint
- `bun run format` - Format code with Prettier

## 🎯 Learning Outcomes

This project demonstrates:
- Modern React development with hooks and TypeScript
- Component composition and reusability
- Responsive web design
- Performance optimization
- Build tools and deployment
- Code organization and architecture

## 📄 License

This is a portfolio project created for demonstration purposes.