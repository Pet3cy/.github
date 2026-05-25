## 2025-01-24 - Accessibility and Performance in Documentation-only Repositories
**Learning:** In repositories where Markdown files are the primary interface, accessibility (avoiding bare URLs) and performance (eliminating redirect chains) are key micro-UX improvements. Screen readers benefit significantly from descriptive link text, and users experience less latency when links point directly to their final destinations.
**Action:** Always audit Markdown files for bare URLs and use `curl` to verify if links point to redirectors, then update them to direct, descriptive links.
