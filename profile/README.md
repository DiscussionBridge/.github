# DiscussionBridge

DiscussionBridge is a family of focused tools built around **The Bridge**, its
Discourse-powered flagship. Platform-native adapters and addons connect
publishing systems to one durable, forum-governed discussion contract without
turning the product into a generic control plane.

## DiscussionBridge Alpha.19

The coordinated public candidate contains six implementation packages:

- [`discourse-discussion-bridge`](https://github.com/DiscussionBridge/discourse-discussion-bridge)
  — **The Bridge**, the unified Discourse receiving and publishing plugin;
- [`astro-discussion-bridge`](https://github.com/DiscussionBridge/astro-discussion-bridge)
  — Astro and Astro + Starlight publishing, retrieval, and comments;
- [`ghost-discussion-bridge`](https://github.com/DiscussionBridge/ghost-discussion-bridge)
  — a native Ghost integration with its hosting-layer adapter service;
- [`hugo-discussion-bridge`](https://github.com/DiscussionBridge/hugo-discussion-bridge)
  — Hugo publishing, retrieval, and comments;
- [`statamic-discussion-bridge`](https://github.com/DiscussionBridge/statamic-discussion-bridge)
  — one Statamic addon for independently configured Flat, DB, and SSG profiles;
  and
- [`wordpress-discussion-bridge`](https://github.com/DiscussionBridge/wordpress-discussion-bridge)
  — a native WordPress publishing, retrieval, retry, and comments plugin.

The language-neutral wire contract and conformance fixtures live in
[`discussionbridge-adapter-contract`](https://github.com/DiscussionBridge/discussionbridge-adapter-contract).

The shared `v0.2.0-alpha.19` tag and GitHub prereleases identify the exact
candidate prepared for human sandbox installation and configuration. They do
not yet claim development/pre-production, live-demo, production, or final Alpha
acceptance.

Explore the [product](https://discussionbridge.dev/),
[documentation](https://docs.discussionbridge.dev/),
[live demos](https://demo.discussionbridge.dev/), and
[community](https://forum.discussionbridge.dev/).
