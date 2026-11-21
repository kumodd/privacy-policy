# Universal Offline AI (UOAI) — Privacy Policy Repository

Official privacy policy and Google Play Store compliance documents for the **Universal Offline AI (UOAI)** Android applications.

---

## 🌐 Hosted Privacy Policies (GitHub Pages)

When GitHub Pages is enabled on the `main` branch, the following URLs are available:

| App / Document | Package ID | Live URL (GitHub Pages) | Local File |
|---|---|---|---|
| **Privacy Hub (Home)** | — | `https://kumodd.github.io/privacy-policy/` | [`index.html`](file:///Users/kumodyadav/Desktop/PrivacyPilicy/index.html) |
| **UOAI Provider** | `com.uoai.provider` | `https://kumodd.github.io/privacy-policy/uoai-provider/` | [`policies/uoai-provider.html`](file:///Users/kumodyadav/Desktop/PrivacyPilicy/policies/uoai-provider.html) |
| **UOAI Chat** | `com.uoai.chat` | `https://kumodd.github.io/privacy-policy/uoai-chat/` | [`policies/uoai-chat.html`](file:///Users/kumodyadav/Desktop/PrivacyPilicy/policies/uoai-chat.html) |
| **Ecosystem Combined** | Both Apps | `https://kumodd.github.io/privacy-policy/privacy-policy.html` | [`privacy-policy.html`](file:///Users/kumodyadav/Desktop/PrivacyPilicy/privacy-policy.html) |

---

## 📁 Repository Structure

```text
privacy-policy/
├── index.html                    # Root portal / hub for GitHub Pages
├── privacy-policy.html           # Full combined ecosystem privacy policy
├── policies/                     # Dedicated individual app policies
│   ├── uoai-provider.html        # UOAI Provider standalone policy
│   └── uoai-chat.html            # UOAI Chat standalone policy
├── uoai-provider/
│   └── index.html                # Clean URL endpoint for /uoai-provider/
├── uoai-chat/
│   └── index.html                # Clean URL endpoint for /uoai-chat/
└── README.md
```

---

## 🛡️ Core Privacy Commitments

- **100% On-Device:** AI model inference and text extraction run locally on hardware (CPU, GPU, NPU).
- **Zero Cloud Servers:** No remote API servers, prompt relays, or remote LLM calls.
- **Zero Accounts:** No registration, login, or personal identifiers required.
- **Zero Analytics / Telemetry:** No Google Analytics, Firebase, Sentry, or third-party ad networks.
- **Loopback Only:** Internal communication binds exclusively to `127.0.0.1:8765`.
