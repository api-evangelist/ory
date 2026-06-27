---
title: "Can API keys be used to secure AI agents?"
url: "https://www.ory.com/blog/can-api-keys-secure-ai-agents"
date: "2026-06-19"
author: "Damon Tepe"
feed_url: "https://www.ory.com/blog/"
---
Traditional API keys are a major vulnerability for autonomous AI agents, which make API calls on behalf of users using static keys that never expire and permissions that were never properly scoped. The article identifies three critical production problems—unlimited credential lifespans, over-permissioning, and unmanageable secret distribution—and argues Ory Talos replaces static credentials with dynamic, revocable token delegation using token derivation, macaroon-based delegation with cryptographic caveats, IP whitelists, TTL expirations, and identifiable token prefixes for secret scanning.
