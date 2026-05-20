# VoltArmor — Reinforced Cable Protection System

Product website for **VoltArmor**, a field-installable protective sleeve system for EV charging cables.

Designed & developed by [Kavi Design & Engineering Studio](https://designkavi.com)

## 🌐 Live Site

Hosted on GitHub Pages: **https://&lt;your-username&gt;.github.io/voltarmor**

## 📁 File Structure

```
voltarmor/
├── index.html                     # Main website (single-page)
├── img_product_1.jpeg             # Zipper closure detail
├── img_product_2.jpeg             # Dual zipper system
├── img_product_3.jpeg             # Outer sleeve with PROTECTED CABLE label
├── img_product_4.jpeg             # Inner layer cross-section
├── VoltArmor_Brochure.pdf         # Product brochure (EN/IT)
├── VoltArmor_Durability_Report.pdf # Cut-resistance test report (Enel S.p.A.)
└── README.md
```

## 🚀 Deploying to GitHub Pages

### Step 1 — Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it `voltarmor` (or any name you prefer)
4. Set visibility to **Public**
5. Click **Create repository**

### Step 2 — Upload files

**Option A — GitHub web interface (no terminal needed):**
1. Open your new repository
2. Click **Add file → Upload files**
3. Drag all files from this folder into the upload area
4. Click **Commit changes**

**Option B — Git command line:**
```bash
cd voltarmor
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/<your-username>/voltarmor.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → scroll to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Choose branch: `main`, folder: `/ (root)`
5. Click **Save**

Your site will be live at:
```
https://<your-username>.github.io/voltarmor
```

> ⏱ It usually takes 1–3 minutes for the site to go live after enabling Pages.

## ✏️ Customization

| What to change | Where |
|---|---|
| Contact email | Search `info@designkavi.com` in `index.html` |
| Company name / credits | Footer section in `index.html` |
| Product images | Replace `img_product_1–4.jpeg` with new files (keep same filenames) |
| PDF documents | Replace the two `.pdf` files |
| Page title / SEO | `<title>` and `<meta>` tags at top of `index.html` |

## 📬 Contact Section

The **Request a Sample** button opens a pre-filled email to `info@designkavi.com`.
Update this address in `index.html` before publishing.
