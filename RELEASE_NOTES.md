# Proxy Manager release information

## 1.0.0-rc.7

Acceptance candidate, not a production sign-off.

- Live HTTPS update-manifest checks with a five-second timeout and five-minute success cache.
- Version comparison includes numeric release-candidate ordering.
- Admin-only update check API and bilingual Web action.
- Persistent job recovery, pool allocation fixes and native management TLS from prior candidates.

This repository publishes version metadata only. Customer source code, configuration, credentials and private data are not published here. Installation packages are delivered separately to the customer; updates are manually installed after backup. The checker never downloads or executes software.

## Feed

`candidate.json` is the release-candidate channel. No stable production release has been declared. The configured URL uses HTTPS and may be overridden with `PROXY_MANAGER_UPDATE_FEED`.

Maintainers: test and package each release before changing the manifest; update the version, notes and release-information URL, and publish the package SHA-256 alongside the manifest. Do not mark customer-server acceptance complete based solely on local tests.
