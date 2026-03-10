# 📚 Seyfert TypeDocs — Auto-Generated

> This documentation is automatically generated from the [Seyfert](https://github.com/tiramisulabs/seyfert) source code using TypeDoc. No manual updates needed — everything is automated.

---

## 🔄 How It Works

The GitHub Actions workflow:

1. **Checks for updates daily** at 00:00 UTC by cloning the Seyfert repo and reading the latest commit SHA
2. **Compares SHA** against the cached `.last-sha` in this repo
3. **Generates docs** using TypeDoc with the Material theme if a new commit is detected
4. **Saves the new SHA** and commits it to `main`
5. **Deploys directly** to GitHub Pages via GitHub Actions

---

## ⚙️ Configuration

To change the TypeDoc theme or config, edit the workflow file on the `main` branch:
```
.github/workflows/auto.yml
```

---

## 🚀 Trigger Manually

Go to **Actions → Auto Deploy → Run workflow** to force a rebuild at any time.
