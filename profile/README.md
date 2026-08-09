# DiscussionBridge

DiscussionBridge connects published content to durable, forum-governed
discussion communities. The Alpha product family starts with Astro, Starlight,
and Discourse while keeping the connection model suitable for additional site
platforms.

## What it does

- creates or resolves companion topics under forum-owned policy;
- embeds simple, full, or fullInteractive discussion experiences;
- preserves explicit source, topic, community, and operating-identity boundaries;
- supports static-site and checked-in Cloudflare deployment workflows;
- gives Discourse operators a dedicated control plane without making the plugin
  mandatory for every adapter use case.

## Current product surfaces

- [discussionbridge.dev](https://discussionbridge.dev/) — product front door
- [docs.discussionbridge.dev](https://docs.discussionbridge.dev/) — manuals and
  product documentation
- [demo.discussionbridge.dev](https://demo.discussionbridge.dev/) — demonstration
  chooser
- [forum.discussionbridge.dev](https://forum.discussionbridge.dev/) — community
  and support forum

The Astro, Astro + Starlight, and stock Starlight demonstrations are linked from
the demo chooser.

## Repositories

- [`discourse-discussion-bridge`](https://github.com/DiscussionBridge/discourse-discussion-bridge)
  — public Discourse control-plane plugin
- `astro-discussion-bridge` — DiscussionBridge for Astro adapter and package
- `apex`, `docs`, and `demo` — independent product-site sources
- `astro-demo-discussionbridge-dev`,
  `astrostarlight-demo-discussionbridge-dev`, and
  `stockstarlight-demo-discussionbridge-dev` — independent demo sources

The non-plugin source repositories remain private during Alpha preparation.
The archived `discussionbridge.dev` predecessor is retained only as historical
Git provenance and is not an active product or deployment source.

## Support

Use the [DiscussionBridge forum](https://forum.discussionbridge.dev/) for
community support. Formal Alpha support channels and any commercial service
offerings will be published only after their operating boundaries are settled.
