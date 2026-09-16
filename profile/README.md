# DiscussionBridge

**Publish on your site. Discuss on your forum.** DiscussionBridge connects
Discourse with Astro, Ghost, Hugo, Statamic, and WordPress. The Bridge and its
platform integrations support publishing in both directions and bringing
comments to your pages.

## Start here

- [Explore the live demos](https://demo.discussionbridge.dev/) and their
  [Discourse publishing matrix](https://demo.discussionbridge.dev/discourse/).
- [Download and install](https://discussionbridge.dev/download/) a component.
- Read the [operator guide](https://docs.discussionbridge.dev/alpha-operator-guide/),
  [platform profiles](https://docs.discussionbridge.dev/platform-profiles/), and
  [dated versions and live status](https://docs.discussionbridge.dev/versions-and-live-status/).
- Ask questions in the [community forum](https://forum.discussionbridge.dev/)
  or use [Alpha support](https://discussionbridge.dev/support/).

## Product family

| Component | Job |
| --- | --- |
| [The Bridge — DiscussionBridge for Discourse](https://github.com/DiscussionBridge/discourse-discussion-bridge) | The receiving and publishing plugin, Content Connections, and durable Bridge Records. |
| [DiscussionBridge for Astro](https://github.com/DiscussionBridge/astro-discussion-bridge) | Astro and Astro + Starlight publishing, retrieval, and comments. |
| [DiscussionBridge for Ghost](https://github.com/DiscussionBridge/ghost-discussion-bridge) | Ghost integration plus a separately hosted adapter service. |
| [DiscussionBridge for Hugo](https://github.com/DiscussionBridge/hugo-discussion-bridge) | Trusted-build publishing, retrieval, and comments. |
| [DiscussionBridge for Statamic](https://github.com/DiscussionBridge/statamic-discussion-bridge) | One addon for independently configured Flat, DB, and SSG profiles. |
| [DiscussionBridge for WordPress](https://github.com/DiscussionBridge/wordpress-discussion-bridge) | Native publishing, retrieval, retry, and comments plugin. |

The [DiscussionBridge Adapter Protocol](https://github.com/DiscussionBridge/discussionbridge-adapter-contract)
is the shared wire contract and conformance fixture set; it is not a seventh
platform adapter. Each component has its own versioned GitHub release. The
exact current releases and installed sandbox/demo versions are tracked in
[Versions and Live Status](https://docs.discussionbridge.dev/versions-and-live-status/),
not inferred from a single family tag or from a moving `main` branch.

DiscussionBridge is in **Alpha**. Human-operated sandbox installs and live
demonstrations are separate from development/preproduction promotion and final
release acceptance. The [documentation](https://docs.discussionbridge.dev/)
states those boundaries explicitly.
