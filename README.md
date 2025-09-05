# Flow State: Non-Coding AI Workflows

Interactive demo presentation exploring powerful AI workflows without traditional programming.


## About This Presentation

This Slidev presentation demonstrates three key AI workflows:
- **Creative Production**: AI video generation using Veo 3, CapCut, and programmatic tools like Remotion
- **Data Processing**: Large-scale classification using AI CLIs
- **Content Creation**: AI-assisted writing and meta-analysis techniques

## Project Structure

- `slides.md` - Main presentation content
- `public/` - Static assets (images, etc.)
- `package.json` - Dependencies and scripts
- `dist/` - Production build output (generated)

## Tech Stack

Built with [Slidev](https://sli.dev/) using the `the-unnamed` theme.


## Getting Started

### Development

```bash
# Install dependencies
pnpm install

# Start dev server
pnpm dev

# Open http://localhost:3030
```

### Build for Production

```bash
# Build static site
pnpm build

# Preview production build
pnpm preview
```

## Deployment to Vercel

### Option 1: Deploy with Vercel CLI

```bash
# Install Vercel CLI
pnpm add -g vercel

# Build and deploy
pnpm build
vercel --prod
```

### Option 2: Deploy via GitHub

1. Push this repository to GitHub
2. Connect your GitHub repo to Vercel
3. Use these build settings:
   - **Build Command**: `pnpm build`
   - **Output Directory**: `dist`
   - **Install Command**: `pnpm install`