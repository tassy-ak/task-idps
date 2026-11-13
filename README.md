# Intelligent Intrusion Detection and Prevention System (IDPS)

A web-based security monitoring project built with React, TypeScript and Vite. The interface presents security monitoring views for detected threats, blocked IP addresses, installation/setup and application settings.

**Live application:** https://idpsi.lovable.app/  
**Repository:** https://github.com/tassy-ak/task-idps

## Project areas

- **Threat monitoring:** a dedicated view for reviewing threat information.
- **Blocked IPs:** a page for viewing blocked IP address entries.
- **Settings:** application configuration interface.
- **Authentication:** sign-in interface and shared authentication context.
- **Installation:** setup guidance presented in the application.

The repository also contains packet generation, packet analysis and threat mitigation service modules.

## Technology stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui and Radix UI components
- Supabase JavaScript client

## Run locally

### Prerequisites

- Node.js
- npm

### Setup

```bash
git clone https://github.com/tassy-ak/task-idps.git
cd task-idps
npm install
npm run dev
```

Vite prints the local development URL in the terminal.

### Production build

```bash
npm run build
```

### Lint

```bash
npm run lint
```

## Configuration

The application uses Supabase client integration. Configure the required environment variables in a local `.env` file according to the Supabase project settings. Do not commit credentials, API keys, or secrets.

## Notes

This repository describes the web application and its current code structure. Detection and mitigation behaviour should be evaluated against the configured data sources and runtime environment before being treated as production-grade network protection.
