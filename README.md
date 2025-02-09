# My Current Tech Stack

The tech stack I use for seamless web development - from local setup to production deployment in minutes.

## Prerequisites

- Vercel account linked to GitHub

## Setup

1. Create empty GitHub repo (private/public)
   - Use lowercase with hyphens for repo name (required by Next.js)
   - Example: `web-development-2025`

2. Initialize Next.js project:
   ```bash
   # Clone and navigate to repo
   git clone <repo-url>
   cd <repo-name>
   
   # Initialize Next.js in repo root
   npx create-next-app@latest .
   # Just select default options (TypeScript, Tailwind CSS, etc)
   ```

3. Local development:
   ```bash
   npm run dev
   ```

4. Deploy:
   - Go to Vercel dashboard → Add project
   - Select repo → Deploy
   - Site available at `your-repo-name.vercel.app`
   - Domains easily purchasable and attachable to your site directly through Vercel UI

5. Development workflow:
   - Use Cursor's agent mode for AI-driven development
     Example: "Create a modern, minimalistic blog with responsive design using Tailwind CSS and shadcn/ui components for a sleek UI"
   - Push to main triggers automatic deployment

6. Auth & Storage:
   - Basic state/data can be handled with cookies
   - For production needs:
     - Clerk: Authentication only
     - Firebase: Full auth and storage solution
     - Supabase: Full auth and storage solution

That's it! Each push to main automatically deploys to your Vercel domain.
