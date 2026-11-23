ACADEMY OF MEDICAL LABORATORY SCIENCE — PROFESSIONAL PORTAL STARTER
Administrator display name: Pravin

This is a starter project, not a deployed live website. It provides:
- Academy-branded responsive homepage
- Student sign-in / account creation screen (Supabase Auth)
- Initial Supabase database schema for profiles, subjects, exams, questions and attempts

Before using with real students:
1. Install Node.js (LTS) on your computer.
2. Create a Supabase project at https://supabase.com/
3. In Supabase SQL Editor, run supabase/schema.sql.
4. Copy .env.example to .env.local and add your Supabase project URL and anon key.
5. In a terminal, from this folder run: npm install
6. Run: npm run dev
7. Open http://localhost:3000 to preview.
8. Push the project to a private GitHub repository and import it into Vercel to deploy.
9. Configure Supabase Auth email settings and add an admin profile securely.

IMPORTANT SECURITY / DEVELOPMENT NOTES
- This is a foundation, not a finished production exam platform.
- Exam delivery, timer enforcement, server-side scoring, admin role management,
  question import, result exports and anti-cheating protections still need implementation.
- Do not store correct answers in client-visible data or rely on browser-side scoring
  for formal examinations. Implement scoring in a trusted server/Edge Function.
- The SQL file includes initial tables and only basic student read policies. Add and
  test complete Row Level Security policies before production.
- Keep Supabase service-role keys secret; never put them in NEXT_PUBLIC variables.
- Use a private admin account and strong authentication.

The website can be previewed locally before you buy a domain. Vercel provides a
temporary deployment URL after you connect the repository.
