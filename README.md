# Next.js Landing Page

A modern, responsive landing page built with Next.js 15, TypeScript, and Tailwind CSS, optimized for deployment on Vercel.

## Features

- ⚡ Next.js 15 with App Router
- 🎨 Tailwind CSS for styling
- 📱 Fully responsive design
- 🌙 Dark mode support
- ⚡ Optimized for Vercel deployment
- 🔍 SEO-friendly
- 🎯 TypeScript for type safety

## Getting Started

First, install the dependencies:

```bash
npm install
```

Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
├── app/
│   ├── globals.css       # Global styles and Tailwind directives
│   ├── layout.tsx        # Root layout component
│   └── page.tsx          # Landing page
├── public/               # Static assets
├── next.config.ts        # Next.js configuration
├── tailwind.config.ts    # Tailwind CSS configuration
├── tsconfig.json         # TypeScript configuration
└── vercel.json          # Vercel deployment configuration
```

## Deployment

This project is optimized for deployment on Vercel:

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Import your repository on [Vercel](https://vercel.com)
3. Vercel will automatically detect Next.js and configure the build settings
4. Click "Deploy" and your site will be live!

Alternatively, you can deploy using the Vercel CLI:

```bash
npm install -g vercel
vercel
```

## Customization

- Update the brand name in `app/page.tsx`
- Modify colors in `tailwind.config.ts`
- Add your own features and sections
- Update metadata in `app/layout.tsx` for SEO

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Vercel Documentation](https://vercel.com/docs)
