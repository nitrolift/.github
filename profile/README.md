<div align="center">

<a href="https://nitrolift.cloud">
  <img alt="NitroLift" src="https://capsule-render.vercel.app/api?type=waving&color=0:8B5CF6,50:6366F1,100:06B6D4&height=220&section=header&text=NitroLift&fontSize=90&fontColor=FFFFFF&fontAlignY=40&desc=OTA%20updates%20for%20React%20Native%20%E2%80%94%20without%20handing%20your%20bundles%20to%20a%20third%20party&descSize=16&descAlignY=65&animation=fadeIn" />
</a>

[Website](https://nitrolift.cloud) · [Docs](https://nitrolift.cloud/docs) · [Pricing](https://nitrolift.cloud/pricing)

</div>

---

## What we build

NitroLift is a paid SaaS for shipping OTA bundle updates to React Native and Expo apps with full control over the release pipeline.

- **Native-first SDK.** Telemetry, downloads, install gating, and rollback fire from Swift and Kotlin. We still see install failures even when the JS engine never boots.
- **Built on Nitro Modules.** Typed bridge generated from a single `.nitro.ts` spec — no hand-written TurboModule plumbing.
- **Drop-in for Expo or bare RN.** A config plugin auto-wires `AppDelegate.swift` and `MainApplication.kt`. No `expo prebuild` surgery.
- **CLI, admin UI, and REST API.** Release upload, gradual rollout, environment promotion, key rotation — all scriptable.

## Featured public repos

- 🤖 **[`agent-skills`](https://github.com/nitrolift/agent-skills)** — Cross-tool AI-agent rules so Claude Code, Cursor, Windsurf, GitHub Copilot, Cline, and `AGENTS.md`-aware tools all understand how to integrate NitroLift correctly. Drop-in install via GitHub Action.

Most of our code is private today; we open repos as they stabilize.

## Get started

```bash
npx @nitrolift/cli login          # OAuth flow opens a browser
npx @nitrolift/cli release upload \
  --project <projectId> \
  --environment prod \
  --app-version 1.0.0 \
  --label 1.0.5 \
  --bundle-path ./dist-ios
```

[Full quickstart →](https://nitrolift.cloud/docs/quickstart)

## Contact

- **Sales / demos:** [hello@nitrolift.cloud](mailto:hello@nitrolift.cloud)
- **Security:** [security@nitrolift.cloud](mailto:security@nitrolift.cloud)
- **Bug reports:** GitHub issues on the relevant repo

---

<div align="center">
<sub>© NitroLift</sub>
</div>
