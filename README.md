# my-resume
## About This Repository

This repository contains my up-to-date resume written in LaTeX.
The source code is publicly available so anyone can use it as a
template to build their own clean, professional resume.

The resume is maintained as a `.tex` file and compiled into a
PDF using LaTeX. Any changes to the source are pushed here
along with the updated PDF, so the latest version is always
available to download directly from this repo.

Feel free to fork this repository, use the template, and
customize it with your own details.

# 📄 LaTeX Resume — Step by Step Guide

A clean, professional resume built using LaTeX. This repository contains
the source code and a compiled PDF of my resume.

---

## 🛠️ Prerequisites

Before you start, make sure you have the following installed:

- **LaTeX Distribution** — [TeX Live](https://tug.org/texlive/) (Linux/Windows)
  or [MacTeX](https://tug.org/mactex/) (Mac)
- **Editor** — [VS Code](https://code.visualstudio.com/) with the
  [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
  extension, or use [Overleaf](https://www.overleaf.com/) (online, no install needed)
- **Git** — to clone and push changes

---

## 🚀 Getting Started

### Step 1 — Clone the Repository

```bash
git clone https://github.com/tanay-codes/resume.git
cd resume
```

### Step 2 — Open the LaTeX File

Open `resume.tex` in your editor (VS Code or Overleaf).

### Step 3 — Edit Your Details

Update the following sections in `resume.tex` with your information:

- **Personal Info** — Name, email, phone, LinkedIn, GitHub
- **Education** — College, degree, year, GPA/percentage
- **Experience** — Company, role, duration, bullet points
- **Projects** — Project name, description, tech stack, links
- **Skills** — Languages, frameworks, tools
- **Achievements** — Certifications, awards, competitive programming

### Step 4 — Compile to PDF

**Using VS Code:**
Press `Ctrl + Alt + B` to build. The PDF will be generated automatically.

**Using Terminal:**
```bash
pdflatex resume.tex
```

**Using Overleaf:**
Click the **Recompile** button. Download the PDF from the top-left menu.

### Step 5 — Push Changes to GitHub

```bash
git add resume.tex resume.pdf
git commit -m "Update resume"
git push origin main
```

---

