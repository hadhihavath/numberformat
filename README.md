# 📞 Phone Number Formatter

A zero-dependency, browser-only tool to clean and reformat messy phone numbers into standard **E.164 / dialable format**.

**Live demo**: deploy via GitHub Pages (see below)

---

## What it does

Paste phone numbers in any messy format — with spaces, dashes, brackets — and get clean, dialable strings like:

```
+918089400844,+918138804749,+919746886380
```

### Supported input formats

| Input | Output |
|---|---|
| `+91 95267 27017` | `+919526727017` |
| `+971 54 377 3039` | `+97154377303` |
| `+91 751 078 4417` | `+917510784417` |
| `9847333254` (10-digit IN) | `+919847333254` |
| `09847333254` (STD style) | `+919847333254` |

### Features
- ✅ Auto-detects country code from `+` prefix
- ✅ Handles Indian 10-digit numbers automatically
- ✅ Converts `00xxx` IDD prefixes to `+xxx`
- ✅ Configurable separator: comma, newline, space, pipe, or custom
- ✅ Skipped/unrecognised numbers listed separately
- ✅ One-click copy to clipboard
- ✅ **100% client-side — no data leaves your browser**

---

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set Source to `main` branch, `/ (root)`
4. Visit `https://<your-username>.github.io/<repo-name>/`

That's it — no build step, no npm install.

---

## Local usage

Just open `index.html` in any browser:

```bash
open index.html
# or
python3 -m http.server 8080
```

---

## License

MIT
