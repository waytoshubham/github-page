# 🌐 Host a Static Website with GitHub Pages

This repository contains a basic HTML file that demonstrates how to host a static website using **GitHub Pages**.
---
## 🧾 Objective
Deploy a simple static HTML website using GitHub Pages — free and easy hosting for personal or project web pages.
---
## 🛠 Tools Used
- GitHub
- GitHub Pages
- HTML
- CSS (optional)
---

## 🚀 Steps to Deploy 

### 1. Create Your HTML File

- Create a file named `index.html` with your website content.

Example:

```html
<!DOCTYPE html>
<html>
<head>
  <title>My GitHub Page</title>
</head>
<body>
  <h1>Hello, GitHub Pages!</h1>
  <p>This is my first hosted website.</p>
</body>
</html>

```
---

### 2. Create a New Repository on GitHub

- Go to GitHub

- Click on + → New repository

- Name it (e.g., my-github-page)

- Keep it Public

- Do NOT add a README (optional)

### 3. Upload Your Website Files
Option A: Using Git
```
    git init
    git add .
    git commit -m "Initial commit"
    git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
    git push -u origin master
```

Option B: Manual Upload

  -  Click on Add file → Upload files

  -  Drag and drop your index.html (and other files)

  -  Click Commit changes


### 4. Enable GitHub Pages

   - Go to the repository → Settings → Pages

   - Under Source, select:

   - Branch: main (or master)

   - Folder: / (root)

   - Click Save

### 5. Visit Your Live Website 🌍

**After a few seconds, GitHub will generate a live link:**

## https://waytoshubham.github.io/github-page/

---

