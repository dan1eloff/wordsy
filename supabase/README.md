# Supabase setup

Project `wordsy`. Tables `words`, `profiles` (RLS: own rows), `admins`; RPC `is_admin`, `admin_overview`, `admin_user_words` (admin-only, checked inside).

Email templates (Authentication → Emails → Templates):
- **Confirm signup** — subject `Подтверди почту в Wordsy`, body `confirm-signup.html`
- **Reset password** — subject `Новый пароль для Wordsy`, body `reset-password.html`

URL configuration (Authentication → URL Configuration):
- Site URL: `https://dan1eloff.github.io/wordsy/`
- Redirect URLs: `https://dan1eloff.github.io/wordsy/**`
