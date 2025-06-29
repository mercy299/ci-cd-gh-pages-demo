
# 🚀 CI/CD Deployment Pipeline with GitHub Actions & GitHub Pages

This project demonstrates a CI/CD pipeline that automatically:
- Lints code
- Runs tests
- Builds the project
- Deploys the output to GitHub Pages

## 📁 Project Setup

1. Clone the Repo
2. Run `npm install`

## 🧪 Lint & Test Locally

```bash
npm run lint
npm test
```

## 🛠️ CI/CD Pipeline Setup

See `.github/workflows/deploy.yml`.

## 🌐 Deployment

1. Set the `homepage` field in `package.json`
2. Enable GitHub Pages in repo settings (branch: `gh-pages`)
3. Push to `main`

## ✅ Live URL
```
https://mercy299.github.io/ci-cd-gh-pages-demo/
```
