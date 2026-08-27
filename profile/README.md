# DiscussionBridge

DiscussionBridge connects an Astro page to one durable, forum-governed
Discourse topic.

The current Alpha consists of:

- `discourse-discussion-bridge` — a default-disabled Ruby Discourse plugin that
  authenticates a dedicated connection, applies forum-owned policy, creates or
  resolves one canonical page-to-topic mapping, exposes bounded operator
  evidence/recovery, and qualifies a comments-only `fullInteractive` embed;
- `astro-discussion-bridge` — the required Astro-side consumer that keeps the
  connection secret server-side, requests controlled creation, stores the topic
  binding, and renders the mapped Discourse discussion; and
- Discourse Core — owner of composer/actions, authentication, sessions,
  authorization, moderation, and post persistence.

This Alpha does not promise a general API-key publishing framework, multiple
independent platform adapters, multi-forum orchestration, or a managed SaaS
control plane. The plugin also does not provision servers, containers, DNS,
TLS, mail, backups, or provider resources.

Public product information remains at
[discussionbridge.dev](https://discussionbridge.dev/), with community support
at [forum.discussionbridge.dev](https://forum.discussionbridge.dev/). Release
and installation claims will be made only after the exact plugin and adapter
candidates pass their separate review, test, install, rollback, and combined
human-acceptance gates.
