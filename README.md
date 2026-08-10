# ASBOG Study App v5.1 Cloud

GitHub Pages + Supabase version with per-user cloud progress.

Replace the repository-root `index.html` with this file.

Supabase requirements:
- `study_progress` table
- RLS policies limiting rows to `auth.uid() = user_id`
- `SELECT`, `INSERT`, and `UPDATE` grants for `authenticated`

The embedded Supabase credential is a publishable browser key, not a secret key.
