# Full Stack RSVP App | Next.js 15, Supabase and Resend 

<p>A sleek and efficient RSVP app to manage guest invitations, track plus-ones, and share event details. It leverages Supabase for authentication and storage, Resend for email notifications, and the Google Maps API for venue location. Built with Next.js and TypeScript, styled using Tailwind CSS and ShadCN, this app ensures a smooth user experience for hosts and guests alike.</p>

## Technologies used

- [Next.js](https://nextjs.org/)
- [Supabase](https://supabase.com/)
- [Resend](https://resend.com)
- [Shadcn](https://ui.shadcn.com/)
  
## Getting started

First, add your ENV's to `.env.local` file:

```bash
NEXT_PUBLIC_SUPABASE_URL=your-project-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key/api-key
RESEND_API_KEY=your-resend-api-key
EMAIL_TO=email where you'll receive notifications. It needs to be the email you used to create the API key in Resend.
```
Then, install the dependencies:
  
```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

## Supabase

### Add User

- Go to your Supabase account
- `Authentication`
- `Add user` and create your admin user

### Create `rsvps` Table


#### Set Email to be **unique field**


### Add Row Level Security Policies

#### Allow anonymous inserts 

#### Owner access 


Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.
