��#   S t a t i c w e b 
# 🚀 Next.js Boilerplate

A **modern and scalable** Next.js boilerplate to kickstart your projects with best practices, clean architecture, and optimized performance.

## 📌 Features
✅ **Next.js 14+** - Fast, efficient, and SEO-friendly framework.  
✅ **TypeScript Support** - Strongly-typed codebase for reliability.  
✅ **Tailwind CSS** - Utility-first styling framework for rapid UI development.  
✅ **ESLint & Prettier** - Linting and formatting for clean code.  
✅ **Absolute Imports** - Better project structure and maintainability.  
✅ **Authentication** - Ready-to-use authentication setup.  
✅ **API Routes** - Integrated backend routes using Next.js API.  
✅ **Folder Structure** - Clean and scalable architecture for long-term projects.  

---

## 📂 Project Structure
```plaintext
nextjs-boilerplate/
├── app/                # Core application logic and routing
│   ├── (auth)/         # Authentication pages
│   │   ├── login/
│   │   │   └── page.tsx
│   │   └── register/
│   │       └── page.tsx
│   ├── dashboard/
│   │   ├── page.tsx
│   │   └── layout.tsx
│   ├── api/            # API routes
│   │   └── users/
│   │       └── route.ts
│   ├── layout.tsx      # Main layout
│   └── page.tsx        # Home page
├── components/         # Reusable components
├── lib/                # Core utilities
├── hooks/              # Custom React hooks
├── types/              # TypeScript types
├── styles/             # Global styles
├── public/             # Static assets
├── next.config.js      # Next.js config
├── package.json        # Dependencies
└── tsconfig.json       # TypeScript config
