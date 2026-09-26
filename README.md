# Starlife Agencies

A free-to-host starter website for member registration, package activation/payment submission, viewer submissions, earnings calculation, referral links, and an admin approval dashboard.

## Payment setup
- Paybill: 714777
- Account: 440200282954
- Payment verification: MANUAL

## Packages
- Regular: KES 100/view, activation KES 200
- VIP: KES 120/view, activation KES 250
- Gold: KES 150/view, activation KES 500

## Setup
1. Create a free Supabase project.
2. Open Supabase SQL Editor and run `supabase/schema.sql`.
3. Copy `.env.example` to `.env` and add your Supabase URL and anon key.
4. Run `npm install` then `npm run dev`.
5. Create your first account, then in Supabase Table Editor change that user's `profiles.role` to `admin`.
6. Deploy the folder to Vercel/Netlify for a public link.

Viewer earnings are calculations based on submitted viewers and configured package rates. Submissions remain pending until an administrator verifies them.
