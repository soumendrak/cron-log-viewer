<div align="center">

# ⏱️ Cron Log Viewer

[![GitHub release](https://img.shields.io/badge/version-1.0.0-ff6b35?style=flat-square)](https://github.com/soumendrak/cron-log-viewer/releases)
[![License](https://img.shields.io/github/license/soumendrak/cron-log-viewer?style=flat-square&color=22c55e)](LICENSE)
[![Pages](https://img.shields.io/badge/GitHub%20Pages-live-1a1a2e?style=flat-square&logo=github)](https://soumendrak.github.io/cron-log-viewer)
[![Size](https://img.shields.io/badge/size-%3C20KB-8888aa?style=flat-square)](index.html)

<!-- SVG Logo -->
<img src="./logo.svg" alt="Cron Log Viewer" width="120" />

**Browse, filter, and inspect cron job execution logs — no dependencies, one file, ready to deploy.**

</div>

---

## ✨ Features

- **Pre-populated sample data** — 10 realistic cron log entries demonstrating every feature
- **Table view** with columns: Job Name, Status, Exit Code, Duration, Timestamp
- **Filter by job name** — live text search across all entries
- **Filter by status** — show All, Success, Error, or Running
- **Expandable log output** — click any row to see the full execution log
- **Color-coded badges** — 🟢 success, 🔴 error, 🟡 running
- **Summary stats** — Total Runs, Success Count, Failure Count, Average Duration
- **Dark theme** with customizable CSS custom properties
- **Zero external dependencies** — vanilla HTML, CSS, and JavaScript
- **Fully responsive** — stacked card layout on mobile (<768px, <480px)

## 📸 Screenshot

![Screenshot placeholder](https://via.placeholder.com/800x450/1a1a2e/ff6b35?text=Cron+Log+Viewer+Screenshot)
<!-- Replace the above with a real screenshot once deployed -->

## 🚀 Usage

1. Download [`index.html`](index.html)
2. Open in any modern browser
3. Browse the sample data, try the filters, click rows to expand logs

```
curl -O https://soumendrak.github.io/cron-log-viewer/index.html
open index.html
```

Or serve locally:

```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

## 🎨 Customization

Modify the CSS variables in `:root` to match your brand:

```css
:root {
  --bg: #0f0f1a;
  --surface: #1a1a2e;
  --accent: #ff6b35;
  --text: #e0e0e0;
}
```

To use your own cron log data, replace the `sampleLogs` array in the `<script>` section.

## 📦 Deploy

```bash
git clone https://github.com/soumendrak/cron-log-viewer.git
cd cron-log-viewer
git push origin main
```

Enable **GitHub Pages** in the repo settings (Source: `main` branch, root folder).

## 📄 License

MIT — see [LICENSE](LICENSE).

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/soumendrak">soumendrak</a></sub>
</div>
