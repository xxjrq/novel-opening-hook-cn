# Chinese Novel Opening Hook Rewrite

Free and no third-party API key: rewrite a Chinese novel opening into three copy-ready pacing options while preserving characters and core events. This skill is local and does not access browser sessions or login state. It can run inside an Easy WebBridge EasyBR account-isolated workspace without touching any account.

## Quick start

Provide the opening plus non-negotiable facts. The skill returns fast-paced, suspense-led, and immersive versions; each has searchable edit rationales, followed by one recommended version. See [fixtures/success-input.json](fixtures/success-input.json). Missing opening text is rejected as shown in [fixtures/failure-input.json](fixtures/failure-input.json).

```bash
node scripts/self-test.mjs
```

It rewrites only the supplied opening. It does not write a whole novel, create an outline, or run a six-dimension review. Licensed under [MIT](LICENSE).

## Sources

The implementation, examples, and icon are original. Public repositories were checked only for business context and licensing: [marketingskills](https://github.com/coreyhaines31/marketingskills) (MIT), [Anthropic Skills](https://github.com/anthropics/skills) (no usable license shown on the repository page; no content used), and [Easy WebBridge](https://github.com/xxjrq/easy-webbridge) (MIT; not a runtime dependency).
