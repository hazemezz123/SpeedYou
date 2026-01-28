# SpeedYou

SpeedYou is an Arabic-first web experience for renting electric scooters. It combines a marketing site with a booking flow, dynamic station listings, and customer support pages. The UI leans on motion-driven storytelling, a modern dark/light theme, and responsive layouts to make the experience feel fast and accessible on any device.

## What This Project Includes

- **Landing experience** with hero messaging, feature highlights, and clear calls to action.
- **Booking journey** that guides users to reserve a scooter and learn pricing.
- **Station discovery** with availability chips and location details.
- **Account views** for login, registration, and a simple dashboard entry point.
- **Support content** covering FAQs, terms of use, and a contact form.
- **Dark mode** via a theme toggle, plus motion-driven UI transitions.

## Tech Stack

- React 18 + React Router
- Vite
- Tailwind CSS v4
- Framer Motion
- EmailJS

## Pages & Routes

| Route | Description |
| --- | --- |
| `/` | Landing page with hero, features, and CTA sections |
| `/booking` | Scooter booking flow |
| `/pricing` | Plans and pricing details |
| `/stations` | Station listing and availability |
| `/faq` | Frequently asked questions |
| `/aboutUs` | About the service |
| `/contactUs` | Contact form and social links |
| `/termsOfUse` | Terms of use |
| `/login` | Login form |
| `/register` | Registration form |
| `/dashboard` | User dashboard |

## Project Structure

```
src/
  components/   Reusable UI components
  context/      Theme provider and shared state
  pages/        Route-level pages
  assets/       Local image assets
```

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Install

```bash
npm install
```

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

### Preview

```bash
npm run preview
```

## EmailJS Configuration

The contact form uses EmailJS. Update the service ID, template ID, and public key inside `src/pages/ContactUs.jsx` with your own values before deploying.

## Assets

Static images and icons live under `public/` and are referenced directly in the UI (e.g., landing page imagery and station photos).

## License

This project is provided as-is. Add your preferred license if you intend to publish it.
