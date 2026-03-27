<div align="center">

<!-- Banner -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://airlockapp.io/brand_trans_dark.png" />
  <img alt="Airlock" src="https://airlockapp.io/brand_trans_dark.png" width="320" />
</picture>
<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://airlockapp.io/brand_trans_light.png" />
  <img alt="Airlock" src="https://airlockapp.io/brand_trans_light" width="320" />
</picture>


<br/>

# Airlock

### Human-in-the-loop security for AI coding agents

**Intercept. Review. Approve. Stay in control.**

[![Website](https://img.shields.io/badge/Website-airlockapp.io-6366f1?style=for-the-badge&logo=globe&logoColor=white)](https://airlockapp.io)
[![Docs](https://img.shields.io/badge/Docs-Read%20the%20Docs-10b981?style=for-the-badge&logo=readthedocs&logoColor=white)](https://airlockapp.io/docs)
[![License: MIT](https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](https://opensource.org/licenses/MIT)

</div>

---

## 🔐 What is Airlock?

Airlock is a **human-in-the-loop security platform** that sits between your AI coding agent and the real world. Every shell command, file edit, and tool call your AI agent wants to make is **intercepted and routed to your phone** for explicit approval — before it executes.

> _You stay in the driver's seat. The AI asks permission._

---

## ✨ How It Works

```
┌─────────────────────┐        ┌──────────────────┐        ┌─────────────────┐
│   AI Coding Agent   │──────▶ │  Airlock Enforcer│──────▶ │ Airlock Gateway │
│  (Cursor, Windsurf, │        │  (IDE Extension) │        │   (Cloud Proxy) │
│   Copilot, etc.)    │        └──────────────────┘        └────────┬────────┘
└─────────────────────┘                                             │
                                                                    ▼
                                                         ┌─────────────────────┐
                                                         │    📱 Your Phone     │
                                                         │  Approve / Deny in  │
                                                         │     real-time       │
                                                         └─────────────────────┘
```

1. **Pair** your IDE with the Airlock mobile app using a QR or text code
2. **Work** with your AI coding agent as usual
3. **Review** every agent action on your phone before it runs
4. **Approve or deny** — nothing executes without your say-so

---

## 🛡️ Security Features

| Feature | Details |
|---|---|
| 🔒 **Action Interception** | Hooks into pre-tool-use lifecycle across all supported IDEs |
| 🔐 **End-to-End Encryption** | AES-256-GCM payload encryption with ECDH key exchange |
| ✍️ **Signature Verification** | Ed25519 signatures on every approval |
| 📱 **Mobile Approver** | Real-time push notifications to your phone |
| 📊 **Quota Monitoring** | Per-workspace usage tracking via the Gateway |
| 🔗 **Presence Tracking** | WebSocket-based live session awareness |
| 🔄 **Token Refresh** | Seamless long-session authentication renewal |

---

## 🖥️ Supported IDEs

<div align="center">

| IDE | Extension | Interception Method |
|:---:|:---:|:---:|
| <img src="https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white" /> | Airlock Cursor Enforcer | Hooks (pre-tool-use) |
| <img src="https://img.shields.io/badge/Windsurf-0ea5e9?style=flat-square&logoColor=white" /> | Airlock Windsurf Enforcer | Hooks (pre-tool-use) |
| <img src="https://img.shields.io/badge/VS%20Code%20Copilot-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" /> | Airlock Copilot Enforcer | Hooks (pre-tool-use) |
| <img src="https://img.shields.io/badge/VS%20Code%20Antigravity-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" /> | Airlock Antigravity Enforcer | Chrome DevTools Protocol |

</div>

---

## 📦 Repositories

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/airlockapp/extensions">
        <img src="https://img.shields.io/badge/extensions-TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white" /><br/>
        <strong>🔌 extensions</strong>
      </a>
      <p>IDE enforcer extensions for Cursor, Windsurf, GitHub Copilot, and Antigravity. These are the thin-client gatekeepers that intercept every AI action before it touches your system.</p>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/airlockapp/airlockapp.github.io">
        <img src="https://img.shields.io/badge/website-Astro%20%2B%20React-ff5d01?style=for-the-badge&logo=astro&logoColor=white" /><br/>
        <strong>🌐 airlockapp.github.io</strong>
      </a>
      <p>The official Airlock marketing site and documentation hub at <a href="https://airlockapp.io">airlockapp.io</a>. Built with Astro, React, and Tailwind CSS.</p>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js%2018+-339933?style=flat-square&logo=node.js&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-ff5d01?style=flat-square&logo=astro&logoColor=white)
![React](https://img.shields.io/badge/React-61dafb?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06b6d4?style=flat-square&logo=tailwindcss&logoColor=white)
![VS Code Extensions SDK](https://img.shields.io/badge/VS%20Code%20SDK-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

</div>

---

## 🚀 Get Started

```bash
# 1. Install the Airlock enforcer extension for your IDE from the VS Code Marketplace

# 2. Pair your workspace with the Airlock mobile app
#    Open the extension → scan the QR code or enter the text code

# 3. Start coding with your AI agent — every action is now gated through your phone
```

📖 Full setup guides for each IDE are available in the [documentation](https://airlockapp.io/docs).

---

## 🤝 Contributing

We welcome contributions! Check out the individual repository READMEs for development setup instructions:

- [extensions contributing guide](https://github.com/airlockapp/extensions)
- [website contributing guide](https://github.com/airlockapp/airlockapp.github.io)

All contributions are subject to our [MIT License](https://opensource.org/licenses/MIT).

---

<div align="center">

**Built for developers who want the power of AI agents — without giving up control.**

[airlockapp.io](https://airlockapp.io) &nbsp;·&nbsp; [Docs](https://airlockapp.io/docs) &nbsp;·&nbsp; [Blog](https://airlockapp.io/blog)

</div>
