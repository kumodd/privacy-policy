# Universal Offline AI (UOAI) — Privacy Policy & Developer Docs Repository

Official privacy policy, Google Play Store compliance documents, external developer integration guide, and AI coding assistant prompts for the **Universal Offline AI (UOAI)** Android ecosystem.

---

## 🌐 Hosted Pages (GitHub Pages)

When GitHub Pages is enabled on the `main` branch, the following URLs are available:

| Resource / App | Package ID / Scope | Live URL (GitHub Pages) | Local File |
|---|---|---|---|
| **UOAI Hub (Home)** | — | `https://kumodd.github.io/privacy-policy/` | [`index.html`](index.html) |
| **Developer Integration Guide** | `com.uoai.provider` | `https://kumodd.github.io/privacy-policy/developer-guide/` | [`developer-guide/index.html`](developer-guide/index.html) |
| **AI Implementation Prompt** | Existing Android Apps | `https://kumodd.github.io/privacy-policy/ai-prompt/` | [`ai-prompt/index.html`](ai-prompt/index.html) |
| **UOAI Provider Privacy Policy** | `com.uoai.provider` | `https://kumodd.github.io/privacy-policy/uoai-provider/` | [`policies/uoai-provider.html`](policies/uoai-provider.html) |
| **UOAI Chat Privacy Policy** | `com.uoai.chat` | `https://kumodd.github.io/privacy-policy/uoai-chat/` | [`policies/uoai-chat.html`](policies/uoai-chat.html) |
| **UOAI Keyboard Privacy Policy** | `com.uoai.keyboard` | `https://kumodd.github.io/privacy-policy/uoai-keyboard/` | [`policies/uoai-keyboard.html`](policies/uoai-keyboard.html) |
| **Ecosystem Combined Policy** | Both Apps | `https://kumodd.github.io/privacy-policy/privacy-policy.html` | [`privacy-policy.html`](privacy-policy.html) |

---

## 📁 Repository Structure

```text
privacy-policy/
├── index.html                    # Root portal / hub for GitHub Pages
├── privacy-policy.html           # Full combined ecosystem privacy policy
├── developer-guide/
│   └── index.html                # External Developer Integration Guide (Path A & Path B)
├── ai-prompt/
│   └── index.html                # Copy-paste AI coding prompts for existing Android apps
├── policies/                     # Dedicated individual app policies
│   ├── uoai-provider.html        # UOAI Provider standalone policy
│   ├── uoai-chat.html            # UOAI Chat standalone policy
│   └── uoai-keyboard.html        # UOAI Keyboard standalone policy
├── uoai-provider/
│   └── index.html                # Clean URL endpoint for /uoai-provider/
├── uoai-chat/
│   └── index.html                # Clean URL endpoint for /uoai-chat/
├── uoai-keyboard/
│   └── index.html                # Clean URL endpoint for /uoai-keyboard/
└── README.md
```

---

## 🛡️ Core Privacy Commitments

- **100% On-Device:** AI model inference and text extraction run locally on hardware (CPU, GPU, NPU).
- **Zero Cloud Servers:** No remote API servers, prompt relays, or remote LLM calls.
- **Zero Accounts:** No registration, login, or personal identifiers required.
- **Zero Analytics / Telemetry:** No Google Analytics, Firebase, Sentry, or third-party ad networks.
- **Loopback Only:** Internal communication binds exclusively to `127.0.0.1:8765`.
