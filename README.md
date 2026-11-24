# JFAM Admin Panel

Web admin dashboard for **JFAM Fresh Dairy** (orders, confirmed queue, COD tracking, subscriptions, customers, inventory/products, KPIs, revenue, delivery partners, and data workspace).

## Local Preview
```bash
python3 -m http.server 8765
```
Open `http://localhost:8765/index.html` and sign in with an admin email registered in Supabase (`public.admin_users`).

## Deployment
Configured for static hosting on Vercel via `vercel.json`. Make sure the Supabase admin workspace migration (`supabase/migrations/202611220001_admin_workspace_access.sql` in `Jfam_app`) is applied before use.
