# IBM Street Food Landing Page & watsonx Assistant Integration

A restaurant landing page featuring an embedded **IBM watsonx Assistant** conversational web-chat widget.

---

## 📁 Repository Contents

| File | Type | Description |
| :--- | :--- | :--- |
| `index.html` | HTML5 Webpage | Landing page built on the BootstrapMade "Yummy" template (v5.3.2) customized with "Anil." branding, featuring an integrated IBM watsonx Assistant live chat entry script (`integrationID: 48732431-0bc8-46a6-81ff-c25448accc45`, `au-syd` region). |
| `Yummy.zip` | ZIP Archive (~5.9 MB) | Contains the vendor assets, styles (`assets/css`), scripts (`assets/js`), vendor libraries (`assets/vendor`), and template images (`assets/img`) required by `index.html`. |

---

## 🚀 How to Run & Preview

Because `index.html` references stylesheets, vendor scripts, and images located under `assets/`, the assets inside `Yummy.zip` must be extracted to the root directory for full visual styling:

1. Extract `Yummy.zip` in the repository root so the `assets/` folder is accessible alongside `index.html`.
2. Open `index.html` directly in your browser or serve it using Python:
   ```bash
   python -m http.server 8080
   ```
3. Open `http://localhost:8080` in your web browser. The IBM watsonx web-chat widget launcher will appear in the bottom-right corner.

---

## 📄 License & Attribution

- **Website Template:** Based on the [Yummy](https://bootstrapmade.com/yummy-bootstrap-restaurant-website-template/) template by [BootstrapMade](https://bootstrapmade.com/).
- **Template License:** [BootstrapMade License](https://bootstrapmade.com/license/).

---

## ❓ Questions for Me

- Would you like `Yummy.zip` extracted into the repository (and the zip removed) so that the website can be previewed directly on GitHub or deployed to GitHub Pages?
- Is this repository intended as a demo showcase for your IBM watsonx Assistant chatbot integration?
