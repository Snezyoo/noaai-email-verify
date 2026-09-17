# NOA AI - Email Verification & Password Reset Web Service 🚀

> **Live Deployment:** [https://noaai-email-verify.vercel.app](https://noaai-email-verify.vercel.app/)

This repository powers the email verification redirect handler and password reset portal for the **NOA AI** application.

## Endpoints

- **/** - [Connection Authenticated](https://noaai-email-verify.vercel.app/) verification landing page. Preserves Supabase tokens and auto-redirects to myapp://auth-callback.
- **/open** - [Email Confirmed](https://noaai-email-verify.vercel.app/open/) redirect endpoint.
- **/reset** - [Reset Password](https://noaai-email-verify.vercel.app/reset/) portal with dual show/hide eye toggles, token exchange (PKCE & Hash), and Supabase JS SDK integration.
- **/forgot** - [Forgot Password](https://noaai-email-verify.vercel.app/forgot/) recovery request portal.

## Features

- Built with modern vanilla HTML/CSS and responsive dark glassmorphism styling.
- Zero dependencies — fast global edge CDN distribution via Vercel.
- Direct native Android handshake via deep links (myapp://auth-callback).
