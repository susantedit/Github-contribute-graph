# 🧠 GitHub Commit Lab

<div align="center">

<img src="assets/logo.png" alt="GitHub Commit Lab Logo" width="150">

### Turn Your GitHub Contribution Graph Into Art 🎨

Create custom text, logos, patterns, and pixel-art designs directly on your GitHub contribution graph using automated commits.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)]()
[![GitHub Stars](https://img.shields.io/github/stars/susantedit/Github-contribute-graph?style=social)]()

</div>

---

## ✨ Overview

GitHub Commit Lab is a Python-powered tool that converts a simple `pattern.json` file into real Git commits with historical timestamps.

These commits are pushed to GitHub and displayed naturally on your contribution graph, allowing you to create:

* ✍️ Text
* 🎨 Pixel Art
* ❤️ Custom Designs
* 🚀 Logos
* 🔥 Creative GitHub Profiles

No image manipulation.

No browser tricks.

Just real commits displayed by GitHub itself.

---

## 🕰️ A Time Machine For Your GitHub Graph

Think of this project as a visual time machine.

Many developers:

* Took long breaks
* Created GitHub accounts late
* Learned Git after months or years
* Want to understand how contribution graphs work

GitHub Commit Lab lets you explore how commit history affects contribution visualization by generating commits on specific dates.

It is designed for:

✅ Learning

✅ Experimentation

✅ Open Source Fun

✅ Git Internals Exploration

Not for misleading others about your development experience.

---

## 🖼️ Example Result

### Before & After

![Contribution Graph Example](assets/patternBeforeAfter.png)

---

## ⚡ Features

* 🎨 Design custom contribution artwork
* 📅 Generate commits for historical dates
* 🚀 Push directly to GitHub
* 🧠 Uses simple JSON pattern files
* 🔥 Supports letters, shapes and logos
* 💻 Cross-platform (Windows, Linux, macOS)
* 🆓 Open Source

---

## 🧠 How GitHub Contribution Graph Works

GitHub contribution graphs contain:

| Dimension  | Meaning       |
| ---------- | ------------- |
| 7 Rows     | Days of Week  |
| 52 Columns | Weeks in Year |

Each green square represents activity on a specific day.

This project:

1. Reads your pattern
2. Finds active pixels
3. Maps them to dates
4. Generates commits
5. Pushes them to GitHub

GitHub automatically renders the final artwork.

---

# 🚀 Getting Started

## Step 1 — Generate Pattern File

Create a design using the visual pattern editor:

🌐 https://susantedit.github.io/GITHUB-PATTERN-DESIGNER/

Download:

```text
pattern.json
```

---

## Step 2 — Create New Repository

Create a new GitHub repository.

Recommended:

* Public repository
* Empty repository

Clone it:

```bash
git clone <your-repository-url>
cd <repository-name>
```

---

## Step 3 — Clone This Tool

```bash
git clone https://github.com/susantedit/Github-contribute-graph.git
```

---

## Step 4 — Copy Required Files

Move the following files into your repository:

```text
script.py
pattern.json
requirements.txt
```

Then delete the cloned tool repository.

This prevents nested Git repositories and `.git` conflicts.

---

## Step 5 — Replace Pattern

Replace the existing:

```text
pattern.json
```

with your downloaded pattern file.

---

## Step 6 — Push Initial Setup

```bash
git add .
git commit -m "Initial setup"
git push origin main
```

---

## Step 7 — Run Script

```bash
python script.py
```

Example:

```text
Enter year to draw pattern: 2025
```

The script will:

* Generate commits
* Assign historical timestamps
* Build your contribution artwork

---

## Step 8 — View Your Graph

Visit your GitHub profile.

Navigate to:

```text
Profile → Contributions
```

GitHub may take several minutes to update.

---

## 📁 Project Structure

```text
Github-Contribute-Graph
│
├── script.py
├── pattern.json
├── requirements.txt
├── assets
│   ├── logo.png
│   └── patternBeforeAfter.png
│
└── README.md
```

---

## ❓ FAQ

### Is this modifying GitHub directly?

No.

It creates normal Git commits with specific timestamps.

---

### Are these real commits?

Yes.

Every square comes from a real Git commit.

---

### Can I create text?

Yes.

The pattern generator supports text and custom pixel designs.

---

### Is this allowed?

GitHub allows commits with custom timestamps.

However, use the tool responsibly.

---

## ⚠️ Disclaimer

This project exists for:

* Learning Git internals
* Exploring contribution graphs
* Creative experimentation
* Open-source education

Please do NOT:

* Fake professional experience
* Misrepresent your activity
* Use contribution graphs as proof of skill

Your projects and code matter far more than green squares.

---

## 🤝 Contributing

Contributions are welcome.

You can help by:

* Reporting bugs
* Improving documentation
* Suggesting features
* Creating pull requests

Please read:

```text
CONTRIBUTING.md
```

before contributing.

---

## ⭐ Support The Project

If you found this project useful:

⭐ Star the repository

🍴 Fork it

🛠️ Contribute improvements

Sharing helps the project grow.

---

## 📜 License

Licensed under the MIT License.

See:

```text
LICENSE
```

for details.

---

# ❤️ Creator

Made with passion by **Aura Farmer**

### 🌐 Connect With Me

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?logo=youtube\&logoColor=white)](https://www.youtube.com/@developersusant)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github\&logoColor=white)](https://github.com/susantedit)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin\&logoColor=white)](https://linkedin.com/in/kantaraj-luitel)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?logo=instagram\&logoColor=white)](https://instagram.com/susantgamerz)
[![X](https://img.shields.io/badge/X-000000?logo=x\&logoColor=white)](https://x.com/Susantedit)

---

<div align="center">

### ⭐ If this project helped you, consider starring the repository ⭐

</div>
