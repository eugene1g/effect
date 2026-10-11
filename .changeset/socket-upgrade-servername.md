---
"effect": patch
"@effect/platform-node-shared": patch
---

Add `servername` to `Socket.TlsUpgradeOptions`, so client-side TLS upgrades (STARTTLS-style) send SNI and verify the peer certificate against the intended host instead of Node's `localhost` fallback.
