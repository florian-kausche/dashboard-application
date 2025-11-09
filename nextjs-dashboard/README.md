# Next.js Dashboard Application

A modern dashboard web application built with Next.js, Tailwind CSS, and TypeScript. Features a sidebar navigation, customer and invoice management, and responsive design.

## Features

- Sidebar navigation with active link highlighting
- Dashboard, Invoices, and Customers pages
- Responsive layout for desktop and mobile
- Authentication-ready structure
- Built with Next.js 15, Tailwind CSS, and Heroicons

## Getting Started

### Prerequisites

- Node.js (v18 or newer recommended)
- pnpm (recommended for dependency management)

### Installation

1. Clone the repository:
   ```powershell
   git clone <your-repo-url>
   cd nextjs-dashboard
   ```
2. Install dependencies:
   ```powershell
   pnpm install
   ```

### Running the Development Server

```powershell
pnpm dev
```

- Open [http://localhost:3000](http://localhost:3000) in your browser.
- Dashboard is at `/dashboard`.

### Building for Production

```powershell
pnpm build
pnpm start
```

## Project Structure

```
nextjs-dashboard/
	app/
		dashboard/
		ui/
		...
	public/
	package.json
	tailwind.config.ts
	tsconfig.json
	README.md
```

## Technologies Used

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [Heroicons](https://heroicons.com/)
- [pnpm](https://pnpm.io/)

## Customization

- Edit navigation links in `app/ui/dashboard/nav-links.tsx`
- Update styles in `app/ui/global.css` and Tailwind config

## License

MIT
