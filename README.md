# 3D Model Generator

A modern web application that generates high-quality 3D models from images or text prompts using the Hyper3D API.

## Features

- Generate 3D models from images or text descriptions
- Real-time 3D model preview with orbit controls
- Multiple quality and format options
- Advanced configuration settings
- Responsive design for desktop and mobile

## Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/) with App Router
- **Rendering**: [React Three Fiber](https://docs.pmnd.rs/react-three-fiber) and [Drei](https://github.com/pmndrs/drei)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
- **UI Components**: [shadcn/ui](https://ui.shadcn.com/)
- **Form Handling**: [React Hook Form](https://react-hook-form.com/) with [Zod](https://zod.dev/) validation
- **Development**: [Turbopack](https://turbo.build/pack) for faster builds

## Getting Started

First, install the dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

## Usage

1. Enter a text prompt or upload images describing the 3D model you want to create
2. Adjust advanced settings if needed (quality, format, etc.)
3. Submit and wait for the model to generate
4. View and interact with your 3D model
5. Download the model in your preferred format

## API Integration

This project uses the Hyper3D API for 3D model generation. For more information about the API:
- [Hyper3D Website](https://hyper3d.ai)
- [API Documentation](https://developer.hyper3d.ai)

## Learn More

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs)
- [React Three Fiber Documentation](https://docs.pmnd.rs/react-three-fiber)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)