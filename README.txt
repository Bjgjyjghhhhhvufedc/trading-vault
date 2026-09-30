TRADING VAULT — CONNECTED + INSTALLABLE

Included:
- Supabase email/password login
- Private per-user cloud sync with RLS
- Automatic cloud sync after changes (debounced)
- PWA manifest + service worker for app-style installation
- Offline app shell/cache
- Existing Trading Vault features and Tools & Settings

IMPORTANT:
- The app must be opened from HTTPS (or localhost) for service-worker/PWA installation.
- Never share a Supabase secret/service_role key. The app uses only the publishable key.
- Auto-sync waits about 1.2 seconds after a change, then uploads the current local data.
