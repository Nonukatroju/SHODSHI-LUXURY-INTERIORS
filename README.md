# Shodshi Luxury Interiors Decorators

## Project info

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I edit this code?

Clone the repository, install dependencies, and run the development server:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

## How can I deploy this project?

Deploy using your preferred hosting provider for Vite/React projects.

## Can I connect a custom domain?

Yes, follow your hosting provider's instructions to connect a custom domain.

## Security Policy: Admin Route

- The admin dashboard is only accessible at `/admin_nag`.
- Do NOT add `/admin_nag` or any admin/private routes to public navigation (header, footer, quick links, etc.).
- Only authenticated admin users can access `/admin_nag`. All others are redirected to `/auth`.
- The `/admin` route is reserved and will always redirect to `/auth`.

This is to ensure admin access is never exposed to regular users or bots.
