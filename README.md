# Rubing Chen's Personal CV Website

This repository contains the source code for my personal academic website, which serves as my online CV. The live website is available at:

**[https://anya-rb-chen.github.io/cv/](https://anya-rb-chen.github.io/cv/)**

[![Deploy Hugo site to Pages](https://github.com/Anya-RB-Chen/cv/actions/workflows/hugo.yml/badge.svg)](https://github.com/Anya-RB-Chen/cv/actions/workflows/hugo.yml)

---

## 🛠️ Technology Stack

*   **Framework:** [Hugo](https://gohugo.io/) (a fast static site generator)
*   **Theme:** [hugo-xmin](https://github.com/yihui/hugo-xmin)
*   **Deployment:** [GitHub Actions](https://github.com/features/actions) for continuous deployment to GitHub Pages.

## 🚀 Running Locally

To run this website on your local machine, you need to have Hugo installed.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Anya-RB-Chen/cv.git
    cd cv
    ```

2.  **Start the Hugo server:**
    ```bash
    hugo server
    ```

3.  **Open your browser:**
    Navigate to `http://localhost:1313` to see a live preview of the site. Content will automatically reload when you make changes to the source files.

## 📜 Content

All website content is located in a single file: `content/_index.md`. The site is configured as a simple, single-page layout. The `public/` directory, which contains the generated static site, is not committed to this repository as it is built automatically by the deployment workflow.