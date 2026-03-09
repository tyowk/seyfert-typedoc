# 📚 Seyfert TypeDocs — Auto-Generated

> This documentation is automatically generated from the [Seyfert](https://github.com/tiramisulabs/seyfert) source code using TypeDoc. No manual updates needed — everything is automated.

---

## ⚠️ Notice

**Do not manually edit the `gh-pages` branch.**
All changes will be automatically overwritten by GitHub Actions whenever Seyfert's repo is updated.

If you need permanent changes (e.g. modifying the TypeDoc theme or config), make them on the `main` branch — not on `gh-pages`.

---

## 🔄 How It Works

The GitHub Actions workflow in this repo will:

1. **Check for updates daily** — every day at 00:00 UTC, the workflow clones the Seyfert repo and checks the latest commit SHA
2. **Detect changes** — the SHA is compared against the cached `.last-sha` stored in this repo
3. **Generate docs** — if there's an update, TypeDoc runs automatically with the `typedoc-material-theme` plugin
4. **Auto-deploy** — the generated docs are pushed directly to the `gh-pages` branch and go live on GitHub Pages

The workflow can also be triggered manually at any time from the **Actions** tab.

---

## 🛠️ Configuration

To change something, edit `.github/workflows/auto.yml` on the `main` branch:

| What to change | Location in file |
|---|---|
| Target repo to watch | `env.TARGET_REPO` |
| Cron schedule | `on.schedule.cron` |
| TypeDoc entry point | `Generate docs` step, `--entryPoints` flag |
| Theme or output folder | `Generate docs` step, adjust the command |

---

## 📦 Tech Stack

- [TypeDoc](https://typedoc.org/) — generates documentation from TypeScript source
- [typedoc-material-theme](https://github.com/nicolo-ribaudo/typedoc-material-theme) — Material Design theme for the docs
- GitHub Actions — CI/CD automation
- GitHub Pages — docs hosting

---

## 🔗 Links

- 📖 **Live docs:** [view on GitHub Pages](https://tyowk.github.io/seyfert-typedoc)
- 📦 **Seyfert repo:** [tiramisulabs/seyfert](https://github.com/tiramisulabs/seyfert)
- ⚙️ **Workflow file:**[.github/workflows/auto.yml](.github/workflows/auto.yml)
