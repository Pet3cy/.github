## 2026-05-20 - [Redirect Elimination in Documentation-Only Repos]
**Learning:** In repositories containing only documentation (like .github community health repos), the "application" is the Markdown content. Performance optimizations can be achieved by eliminating URL redirects, which measurably reduces network latency and RTTs for users.
**Action:** Profile URL redirect chains in MD files using `curl` and replace legacy/shortlinks with canonical direct destinations to save hundreds of milliseconds in user-perceived load time.
