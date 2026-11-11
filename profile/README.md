# DiscussionBridge

Publish on your site and discuss on your Discourse forum. DiscussionBridge
connects native publishing on Astro, Ghost, Hugo, Statamic, and WordPress with
Discourse topics. Use Content Connections to choose what can publish and in
which direction.

- [Product site](https://discussionbridge.dev/) and [documentation](https://docs.discussionbridge.dev/)
- [Public demo chooser](https://demo.discussionbridge.dev/) and [sandbox chooser](https://sandbox.discussionbridge.dev/)
- [Community forum](https://forum.discussionbridge.dev/) and [support](https://discussionbridge.dev/support/)

## V4 Alpha

The tags below identify the source builds that passed GitHub Actions. Installed
versions depend on the environment. Use the component README for setup and
package instructions.

| Component | What it does | V4 Alpha source tag |
| --- | --- | --- |
| [DiscussionBridge for Discourse](https://github.com/DiscussionBridge/discourse-discussion-bridge) | The Discourse plugin manages Content Connections, publishing policy, and Bridge Records. | [`v0.4.0-alpha.1.receiver.2`](https://github.com/DiscussionBridge/discourse-discussion-bridge/tree/v0.4.0-alpha.1.receiver.2) |
| [Ghost connector](https://github.com/DiscussionBridge/discourse-discussion-bridge-ghost) | An optional Discourse plugin that connects directly to Ghost for publishing and comments. | [`v0.4.0-alpha.1.ghost.3`](https://github.com/DiscussionBridge/discourse-discussion-bridge-ghost/tree/v0.4.0-alpha.1.ghost.3) |
| [Ghost adapter](https://github.com/DiscussionBridge/ghost-discussion-bridge) | Connects Ghost and Discourse through a separately hosted HTTPS service. | [`v0.4.0-alpha.1.ghost-adapter.1`](https://github.com/DiscussionBridge/ghost-discussion-bridge/tree/v0.4.0-alpha.1.ghost-adapter.1) |
| [DiscussionBridge for WordPress](https://github.com/DiscussionBridge/wordpress-discussion-bridge) | A WordPress plugin for native publishing, retrieval, and comments. | [`v0.4.0-alpha.1.wp.3`](https://github.com/DiscussionBridge/wordpress-discussion-bridge/tree/v0.4.0-alpha.1.wp.3) |
| [DiscussionBridge for Astro](https://github.com/DiscussionBridge/astro-discussion-bridge) | One adapter for plain Astro and Astro with Starlight. | [`v0.4.0-alpha.1.astro.3`](https://github.com/DiscussionBridge/astro-discussion-bridge/tree/v0.4.0-alpha.1.astro.3) |
| [DiscussionBridge for Hugo](https://github.com/DiscussionBridge/hugo-discussion-bridge) | An adapter that publishes, retrieves, and renders discussions through a Hugo build. | [`v0.4.0-alpha.1.hugo.4`](https://github.com/DiscussionBridge/hugo-discussion-bridge/tree/v0.4.0-alpha.1.hugo.4) |
| [DiscussionBridge for Statamic](https://github.com/DiscussionBridge/statamic-discussion-bridge) | One Statamic addon for Flat, Eloquent DB, and SSG profiles. | [`v0.4.0-alpha.1.statamic.4`](https://github.com/DiscussionBridge/statamic-discussion-bridge/tree/v0.4.0-alpha.1.statamic.4) |

The [DiscussionBridge Adapter Protocol](https://github.com/DiscussionBridge/discussionbridge-adapter-contract) defines the shared
wire contract. [V4 R7](https://github.com/DiscussionBridge/discussionbridge-adapter-contract/tree/09d77c0209835c2d996aad294d161f167c7bd838) is the contract baseline for the builds above
and defines 36 Content Connection routes.
