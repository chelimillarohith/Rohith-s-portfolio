# Rohith-s-portfolio
To add your portfolio project to GitHub, follow these steps:

---

### ✅ 1. **Create a GitHub Repository**

1. Go to [GitHub](https://github.com/).
2. Click the **"+"** icon on the top-right corner and select **"New repository"**.
3. Fill in the details:

   * **Repository name**: e.g., `rohith-portfolio`
   * Description (optional): e.g., `My personal portfolio built with HTML and CSS`
   * Choose **Public** or **Private**
   * **Do not** initialize with a README (you’ll add it later)
4. Click **"Create repository"**.

---

### ✅ 2. **Push Your Local Project to GitHub**

Assuming your portfolio files are already in a folder on your computer, follow these terminal/command prompt steps:

```bash
cd path/to/your/portfolio-folder
git init
git remote add origin https://github.com/chelimillarohith/rohith-portfolio.git
git add .
git commit -m "Initial commit - Portfolio website"
git push -u origin master
```

> Replace the URL with your actual GitHub repo URL.

---

### ✅ 3. **Make It Live Using GitHub Pages**

1. Go to the created repository on GitHub.
2. Click on **"Settings"** → **"Pages"** (in the left menu).
3. Under **"Source"**, select the `main` or `master` branch and then click **"Save"**.
4. GitHub will give you a live URL like:

   ```
   https://chelimillarohith.github.io/rohith-portfolio/
   ```

---

### ✅ 4. **Add a README.md File**

Create a simple `README.md` to describe your project. Example:

```markdown
# Rohith Chelimilla - Personal Portfolio

This is my personal portfolio showcasing my skills, projects, education, and certifications. Built using only HTML and CSS.

🔗 Live site: [Click here](https://chelimillarohith.github.io/rohith-portfolio/)

## Features
- Responsive design
- Clean UI with dark mode
- Dynamic section switching
- Hosted on GitHub Pages

## Contact
- [LinkedIn](https://www.linkedin.com/in/rohith-chelimilla-9b45922a7/)
- [Email](mailto:rohithchelimilla@gmail.com)
```

---

Would you like me to generate a `.zip` of your project ready to upload, or help create a `README.md` file for it?
