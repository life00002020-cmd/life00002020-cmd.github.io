# Personal Website

My personal portfolio and CV site, hosted on GitHub Pages.

## 🚀 Deploy to GitHub Pages

### Step 1 — Create GitHub repository

1. Go to [github.com](https://github.com) and log in
2. Click **New repository**
3. Name it exactly: `your-username.github.io`
   - Replace `your-username` with your actual GitHub username
   - Example: if your username is `johndoe`, name it `johndoe.github.io`
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the files

**Option A — Upload via GitHub UI (easiest)**

1. Open your new repository
2. Click **Add file → Upload files**
3. Drag and drop `index.html` and `style.css`
4. Click **Commit changes**

**Option B — Use Git (recommended)**

```bash
# Clone the repo
git clone https://github.com/your-username/your-username.github.io
cd your-username.github.io

# Copy the files into this folder, then:
git add .
git commit -m "Initial commit"
git push origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repository **Settings**
2. Click **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Choose branch: **main**, folder: **/ (root)**
5. Click **Save**

### Step 4 — Visit your site

After ~1 minute, your site will be live at:

```
https://your-username.github.io
```

---

## ✏️ How to customize

Open `index.html` and update:

| What | Where |
|------|-------|
| Your name | `<title>` tag and `<h1>` in the hero section |
| Job title | `.hero-eyebrow` paragraph |
| Bio | `.hero-bio` paragraph |
| Tech stack tags | `.hero-tags` section |
| GitHub / LinkedIn URLs | `.hero-links` and `#contact` section |
| Work experience | `.timeline` section |
| Projects | `.projects-grid` section |
| Email | `<a href="mailto:...">` in contact section |

Open `style.css` to change:

| What | Variable |
|------|----------|
| Accent color (blue links) | `--accent` |
| Background color | `--white` |
| Text color | `--black` |

## 📁 File structure

```
your-username.github.io/
├── index.html    ← main page
├── style.css     ← all styles
├── resume.pdf    ← (optional) add your resume here
└── README.md
```
