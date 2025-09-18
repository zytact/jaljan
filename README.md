# Jaljan

A modern web application built with Next.js, React, and TypeScript.

## Tech Stack

- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript with strict mode
- **Styling**: Tailwind CSS with shadcn/ui (New York style)
- **Linting & Formatting**: Biome
- **Package Manager**: pnpm
- **React**: Version 19

## Prerequisites

- Node.js (version 18 or higher)
- pnpm

## Getting Started

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd jaljan
   ```

2. **Install dependencies**

   ```bash
   pnpm install
   ```

3. **Run the development server**

   ```bash
   pnpm dev
   ```

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Available Scripts

- `pnpm dev` - Start the development server with Turbopack
- `pnpm build` - Build the application for production with Turbopack
- `pnpm start` - Start the production server
- `pnpm lint` - Run Biome linter
- `pnpm format` - Format code with Biome

## Project Structure

```
src/
├── app/                 # Next.js App Router pages
├── components/          # Reusable React components
│   ├── ui/             # shadcn/ui components
│   └── theme-provider.tsx
└── lib/                # Utility functions
```

## Development

- Edit pages in `src/app/`
- Add components in `src/components/`
- Use `src/lib/utils.ts` for utility functions
- Follow TypeScript strict mode and Biome formatting ([VS Code Extension](https://marketplace.visualstudio.com/items?itemName=biomejs.biome))

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run `pnpm lint` and `pnpm format`
5. Submit a pull request
