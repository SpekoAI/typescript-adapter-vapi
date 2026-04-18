# @spekoai/adapter-vapi — skill sheet

> **Status: scaffold-only. Not production-ready.**

## When to use

Don't use this package yet. It's a placeholder for a future Vapi adapter
that will let you configure Vapi assistants to call Speko's proxy
endpoints (STT/LLM/TTS routing + failover) automatically.

If you need Vapi + Speko today, you can configure your Vapi assistant's
custom LLM / custom STT / custom TTS webhooks to point at your own
backend, which itself calls `@spekoai/sdk`. That's a workaround until
this adapter lands.

## What exists today

A scaffolded npm package (`@spekoai/adapter-vapi`) with no runtime API
surface. Version tracks `0.0.0` deliberately so consumers can't
accidentally pin it.

## See also

- README: `spekoai://docs/adapter-vapi-readme`
- Supported adapter today: `spekoai://docs/adapter-livekit-skills`
- Track progress: the SpekoAI roadmap (repo-level).
