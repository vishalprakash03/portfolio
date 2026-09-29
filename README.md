# Developer Portfolio with GitHub Analytics

A modern developer portfolio built with Next.js and Tailwind CSS, designed to showcase personal projects, skills, and live GitHub statistics in a polished single-page experience.

## Overview

This portfolio includes:

- a hero section introducing the developer
- an about section with key skills and experience
- a projects showcase for featured work
- GitHub analytics using the public GitHub API
- repository activity and language insights
- responsive dark-theme UI for modern portfolio presentation

## Tech Stack

- Next.js
- React
- TypeScript
- Tailwind CSS
- Chart.js / react-chartjs-2
- GitHub REST API
- Lucide React

## Features

- Live GitHub profile data
- Public repository stats
- Language usage overview
- Recent repository activity
- Responsive portfolio layout
- Clean dark UI optimized for developer branding

## Project Structure

```bash
.
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── About.tsx
│   ├── Contact.tsx
│   ├── Footer.tsx
│   ├── GithubAnalytics.tsx
│   ├── GithubCharts.tsx
│   ├── Hero.tsx
│   ├── Navbar.tsx
│   ├── Projects.tsx
│   └── Skills.tsx
├── services/
│   └── github.ts
├── types/
├── public/
├── package.json
├── next.config.ts
├── tsconfig.json
├── postcss.config.mjs
├── eslint.config.mjs
└── README.md
```

## Getting Started

1. Install dependencies:

```bash
npm install
```

2. Run the development server:

```bash
npm run dev
```

3. Open your browser at:

```bash
http://localhost:3000
```

## Environment Variables

This project supports a custom GitHub username via environment variable:

```bash
NEXT_PUBLIC_GITHUB_USERNAME=your-github-username
```

If not set, it defaults to:

```bash
vishalprakash03
```

## Build

To create a production build:

```bash
npm run build
```

To start the production server:

```bash
npm run start
```

## Notes

The GitHub data is fetched from the public GitHub API and cached for a short period to keep the portfolio fast while still reflecting recent activity.

## License

This project is for personal portfolio and learning purposes.
