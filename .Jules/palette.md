## 2025-05-14 - [Direct URL Destinations and Descriptive Links]
**Learning:** In documentation-only repositories, the Markdown files are the primary User Interface. UX improvements involve reducing network latency by eliminating redirect chains and enhancing accessibility for screen readers by replacing bare URLs with descriptive link text.
**Action:** Always verify the final destination of URLs using `curl -Ls -o /dev/null -w %{url_effective} <URL>` and ensure links have meaningful descriptions instead of being bare URLs.
