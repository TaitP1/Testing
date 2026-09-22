# Apex Scientific Training & Biomechanics Tracker

Evidence-based 4-day progressive overload program engineered with stretch-mediated hypertrophy research, stimulus-to-fatigue ratio (SFR) optimization, interactive SVG muscle anatomy graphics, and an AI biomechanics coach.

---

## 🚀 How to Drag & Drop into GitHub and Deploy

### Step 1: Create a Repository on GitHub
1. Go to [github.com/new](https://github.com/new).
2. Name your repository (e.g., `apex-training-tracker`).
3. Leave it as **Public**, do **not** check "Add a README", and click **Create repository**.

### Step 2: Drag and Drop Files
1. On the setup page, click the link that says **"uploading an existing file"** (or click **Add file** -> **Upload files**).
2. Unzip your downloaded project and **drag all files and folders** into the GitHub upload area:
   - `.github/` (contains `workflows/deploy.yml`)
   - `components/`
   - `constants/`
   - `services/`
   - `App.tsx`
   - `index.tsx`
   - `index.html`
   - `types.ts`
   - `package.json`
   - `tsconfig.json`
   - `vite.config.ts`
   - `.gitignore`
   - `metadata.json`
3. In the commit box at the bottom, type `Initial commit` and click **Commit changes**.

### Step 3: Enable 1-Click Free Hosting on GitHub Pages
1. In your GitHub repository, click **Settings** (top tab).
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment** -> **Source**, select **GitHub Actions**.
4. That's it! GitHub will automatically trigger the included workflow in `.github/workflows/deploy.yml`, build the application, and provide your live URL (e.g., `https://your-username.github.io/apex-training-tracker/`).

---

## 💻 Running Locally (Optional)

If you wish to test or develop locally on your computer:

```bash
# 1. Install dependencies
npm install

# 2. Start local dev server
npm run dev
```

Visit `http://localhost:3000` in your browser.
