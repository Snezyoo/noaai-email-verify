# NOA AI - Email Verification & Password Reset Web Service

This repository powers the email confirmation redirect and password reset portal for the **NOA AI** application.

## Endpoints

- **/** - Connection Authenticated / Verification landing page. Auto-redirects to myapp://auth-callback while forwarding authentication tokens.
- **/open** - Email verification confirmation endpoint (/open/).
- **/reset** - Supabase password recovery & reset portal with dual show/hide toggles and live validation.
- **/forgot** - Password recovery request portal.

## Deploying to Vercel

1. Log in to [Vercel](https://vercel.com).
2. Click **Add New...** -> **Project**.
3. Import this repository: Snezyoo/noaai-email-verify.
4. Keep the Framework Preset as **Other** and Root Directory as ./.
5. Click **Deploy**.
