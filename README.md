# StudyCubs

StudyCubs is a modern online learning platform that helps students build confidence, skills, and real-world readiness through interactive courses in coding, public speaking, and financial planning.

## Overview

This project is built with Next.js and designed as a responsive, conversion-focused website for an education brand. It showcases courses, testimonials, FAQs, and booking flows to help visitors explore programs and connect with the platform.

## Features

- Landing page with strong conversion-focused sections
- Course highlights for:
  - Public speaking
  - Coding
  - Financial planning
- Testimonials and student trust-building content
- FAQ section for prospective learners
- Calendar/booking integration for demo or enrollment sessions
- Responsive design for desktop and mobile devices
- Clean, modern UI built with Tailwind CSS

## Tech Stack

- Next.js 15
- React 19
- TypeScript
- Tailwind CSS
- Google APIs integration
- React Icons

## Project Structure

```bash
study-cubs/
├── src/
│   ├── app/
│   ├── components/
│   ├── constants/
│   ├── utils/
│   └── types/
├── public/
├── package.json
├── next.config.ts
├── tailwind.config.ts
├── tsconfig.json
├── eslint.config.mjs
├── README.md
└── .gitignore
```

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js 18+
- npm, yarn, or pnpm

### Installation

```bash
git clone <your-repository-url>
cd study-cubs
npm install
```

### Run the app

```bash
npm run dev
```

Then open:

```bash
http://localhost:3000
```

## Available Scripts

```bash
npm run dev      # Start the development server
npm run build    # Build the production app
npm run start    # Start the production server
npm run lint     # Run ESLint checks
```

## Environment Variables

If your project later requires API keys or secrets, create a `.env.local` file in the project root and add the required values.

Example:

```bash
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

## Screenshots

A few project screenshots are stored in the screenshots folder and can be showcased here:

<div align="center">
  <img src="public/screenshots/Screenshot%202026-10-02%20at%2011.05.06%E2%80%AFPM.png" alt="StudyCubs homepage preview" width="900" />
</div>

<div align="center">
  <img src="public/screenshots/Screenshot%202026-10-02%20at%2011.05.17%E2%80%AFPM.png" alt="StudyCubs course section preview" width="900" />
</div>

<div align="center">
  <img src="public/screenshots/Screenshot%202026-10-02%20at%2011.05.25%E2%80%AFPM.png" alt="StudyCubs testimonial section preview" width="900" />
</div>

<div align="center">
  <img src="public/screenshots/Screenshot%202026-10-02%20at%2011.05.33%E2%80%AFPM.png" alt="StudyCubs additional preview" width="900" />
</div>

## Deployment

This project is ready to be deployed on platforms like:

- Vercel
- Netlify
- Any Node.js-compatible hosting platform

For Vercel, the recommended deployment is usually straightforward with a standard Next.js project setup.

## Contributing

1. Create a feature branch
2. Make your changes
3. Run lint/build checks
4. Open a pull request

## License

This project is currently unlicensed unless you add a specific license file for your organization.

## Contact

For business or course-related inquiries, use the contact and booking flows included in the website.

---

This README is intentionally structured so you can add screenshots and project details as you continue developing the site.
