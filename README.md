# Cast & Render — 3D Object Studio

A scroll-scrubbed video landing page featuring frame-by-frame scrubbing and sequential cross-fading typography panels.

## Deploying to Vercel

This project is configured for one-click deployment to [Vercel](https://vercel.com).

### Option 1: Vercel CLI
```bash
npm install -g vercel
vercel
```

### Option 2: Git Integration (GitHub / GitLab / Bitbucket)
1. Push this repository to your Git provider.
2. Go to [Vercel Dashboard](https://vercel.com/new).
3. Import this repository.
4. Vercel will automatically detect the configuration from `vercel.json`:
   - **Framework Preset**: Vite
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
5. Click **Deploy**.

### Option 3: Direct Static Hosting
Because `index.html` is completely self-contained with embedded CSS and vanilla JS, you can also deploy `index.html` directly to any static file host without running a build step.
