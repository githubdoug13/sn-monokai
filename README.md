# sn-monokai-pro

A Monokai Pro (Classic filter) theme for [Standard Notes](https://standardnotes.com).

---

## Install

1. Open Standard Notes
2. Navigate to **Plugins → Install Custom Plugin**
3. Paste the install URL:

---

## Palette

Based on the Monokai Pro Classic filter by [Wimer Hazenberg](https://monokai.pro).

| Role | Color | Hex |
|---|---|---|
| Background | Deep olive-black | `#272822` |
| Panel / Sidebar | Darker chrome | `#1e1f1c` |
| Hover / Selection | Highlight surface | `#3e3d32` |
| Primary Text | Warm off-white | `#f8f8f2` |
| Muted Text | Warm grey | `#90908a` |
| Accent (selection) | Orange | `#fc9867` |
| Success | Green | `#a9dc76` |
| Warning | Yellow | `#ffd866` |
| Danger | Pink | `#f92672` |
| Info / Focus | Cyan | `#78dce8` |

---

## Updating

After making changes to `monokai.css`:
```bash
git add -A
git commit -m "fix: description of change"
git tag v1.x.x
git push origin main --tags
```

Update the version and jsDelivr tag references in `ext.json`, push, then reinstall the theme in Standard Notes.

---

## Compatibility

- **Desktop app** — full support
- **Web app** — full support via jsDelivr CDN
- **Mobile** — CSS variables apply automatically per Standard Notes spec