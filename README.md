# Biogear Microscope Viewer — release feed

Update feed and release payloads for **Biogear Microscope Viewer**.
This repository contains **no source code** — the application source is private.

- `appcast.xml` — the Sparkle update feed the app polls.
- Release assets — the `.zip` payloads and `.delta` patches the feed points at.

Sparkle fetches the feed and the archives without authenticating, so both have to be
publicly reachable; that is the only reason this repository exists. Everything here is
signed with the project's EdDSA key and verified by the updater before installation.

Application © Biogear. See the app's About window for third-party notices.
