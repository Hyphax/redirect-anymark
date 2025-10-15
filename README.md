# redirect-anymark

**Purpose:** Permanent edge redirect from `anymark.io` to `https://anymark.co`

- All paths and query parameters are preserved (e.g., `/docs?page=1` → `https://anymark.co/docs?page=1`)
- HTTP 301 permanent redirect configured via `vercel.json`
- Deployed on Vercel with zero build steps
- No frameworks, dependencies, or build configuration required
- Edge-optimized redirect at CDN level
