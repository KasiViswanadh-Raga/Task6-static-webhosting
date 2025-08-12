# 🌐 Static Website Deployment — GitHub Pages (Task 6)

This repository contains a **real-world static website** built with HTML and CSS, deployed using **GitHub Pages** as part of my DevOps internship Task 6.

---

## 📜 Project Overview
The goal of this task was to host a simple static site for free using GitHub Pages.  
The site demonstrates:
- A **dark, modern portfolio layout**
- Responsive design (works on desktop & mobile)
- Sections for Projects, About, and Contact
- Free hosting via GitHub Pages

---

## 🛠 Tech Stack
- **HTML5** — structure of the web page
- **CSS3** — styling and layout
- **Git & GitHub** — version control and hosting
- **GitHub Pages** — free static site deployment

---

## 🚀 Deployment Steps

### 1️⃣ Create and Push Code
```bash
# Create folder & add files
mkdir task6-static-site && cd task6-static-site
# Add index.html, styles.css, README.md

git init
git add .
git commit -m "Initial commit: add static site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
2️⃣ Enable GitHub Pages
Go to GitHub → Repository → Settings → Pages

Under Source, select Branch: main and / (root) folder

Click Save

GitHub will provide a live site URL (e.g. https://<your-username>.github.io/<repo-name>/)

🔄 Updating the Website
To make changes:

bash
Copy
Edit
# Make edits locally
git add .
git commit -m "Updated hero section text"
git push
GitHub Pages will automatically redeploy with the new changes.

📂 Project Structure
bash
Copy
Edit
.
├── index.html    # Main HTML file
├── styles.css    # CSS styling file
├── README.md     # Project documentation
🌟 Live Demo
Live Site: https://kasiviswanadh-raga.github.io/Task6-static-webhosting/
GitHub Repo: https://github.com/KasiViswanadh-Raga/Task6-static-webhosting

❓ Interview Questions & Answers
1. What is GitHub Pages?
A free static site hosting service from GitHub that serves HTML/CSS/JS directly from a repository.

2. Can you host dynamic apps here?
No. GitHub Pages only serves static files. Dynamic features must come from client-side JavaScript or external APIs.

3. What are the limits of GitHub Pages?

Static content only

Repo size should be reasonable (under ~1GB)

Bandwidth limit (soft limits, large-scale sites not ideal)

4. How do you update the website?
Commit & push changes to the configured branch; GitHub Pages redeploys automatically.

5. What happens when you delete the repo?
The live site is removed; URL will return 404.

6. What is the default file that loads?
index.html in the selected folder.

7. Can you use a custom domain?
Yes — configure a CNAME file and set DNS records to GitHub Pages.

📌 Author
Name: Raga Kasi Viswanadh
Role: DevOps Intern
GitHub: KasiViswanadh-Raga
Email: kasiviswanadh4321@gmail.com
