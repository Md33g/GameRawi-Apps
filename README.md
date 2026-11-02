<img width="512" height="512" alt="Untitled112_20261102163704" src="https://github.com/user-attachments/assets/1a3d61c7-30a8-4e07-b516-e2506905a368" />

## ✨ What's new in v2.3.0

### ✍️ Simpler editor — just type
The editor is now **plain text**. Everything that added friction is gone:

- ✅ Note body preserves line breaks exactly (`white-space: pre-wrap`)
- ✅ Single-note export is now `.txt` (was `.md`)
- ✅ Templates are plain text now (Meeting, Todo, Journal, Idea, Recipe)

### 🛡️ Data safety
- Storage key unchanged (`gamerawi_notes_v3`) — **your notes carry over safely**.
- Legacy `tags` fields are kept in the JSON (harmless) and simply ignored by the UI.
- Any Markdown-looking body from v2.2 displays **as literal text** — open and edit as needed.

---

## 📋 Full feature list

| | Feature |
|---|---|
| 📝 **Notes** | Create · edit · autosave · pin · duplicate · archive · delete · trash · restore · permanent delete |
| 📁 **Organize** | Folders · sort by updated/created/title · grid or list layout |
| 🔍 **Search** | Live search across title + body |
| 🎨 **Personalize** | 12 themes (6 free + 6 premium demo) · custom accent · dark/light · 16 FOSS fonts · font size · line height · corner radius |
| 😀 **Notes that feel yours** | Emoji icon per note (any emoji from your system keyboard) · color label per note (8 presets) |
| 🌍 **Bilingual** | Full Arabic/RTL · per-note Auto/RTL/LTR · whole-app RTL |
| 🎬 **Backgrounds** | Starfield · Particles · Nebula · Waves · None — with intensity & speed sliders |
| 📝 **Templates** | Blank · Meeting · Todo · Journal · Idea · Recipe |
| 💾 **Data** | JSON export/import (full backup) · export single note as `.txt` · copy to clipboard · clear / factory reset |
| 🔐 **Privacy** | 100% offline · on-device only · zero external requests · zero tracking |
| ♿ **Accessible** | ARIA · focus rings · `prefers-reduced-motion` · keyboard shortcuts (`Ctrl+N`, `Esc`) |
| 📱 **Responsive** | Portrait · landscape · all aspect ratios · safe-area insets · ultrawide |

---

## 🧪 Tested in

- tablet · phone · foldable · ultrawide
- Arabic (RTL) and English (LTR) mixed content

---

## ⚠️ Notes & caveats

- **Not encrypted.** Notes sit in `localStorage` on your device. Do not store classified, medical, financial, or legally privileged information.
- **Export regularly.** Browsers and OSes may clear local storage without notice. Use **Settings → Export**.
- **Not for compliance use.** Not intended for HIPAA, GDPR data processing, PCI-DSS, or similar regulated workflows.
- **Premium is a demo.** The Premium toggle is a purely local cosmetic unlock. No payment is processed, no data is sent, no real transaction occurs.
- **No affiliation.** Not affiliated with, endorsed by, or sponsored by any company, government, or organization.

---

## 💙 Credits

**Made with 💙 by Mohamed Elba.**

Fonts referenced via local stacks — all SIL OFL or Apache 2.0 (Inter, IBM Plex, Lato, Source Sans Pro, Ubuntu, Cantarell, Atkinson Hyperlegible, Noto Naskh Arabic, Amiri, JetBrains Mono, Fira Code, DejaVu). If a font isn't installed, the system fallback is used. **No Google Fonts, no network fetch, ever.**
