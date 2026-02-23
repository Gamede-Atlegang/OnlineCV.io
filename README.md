# Online CV

A single-page professional CV and portfolio, built for ICE 1. Ready to host on **GitHub Pages**, Netlify, or Vercel.

## Before You Submit

1. **Replace all placeholder content** in `index.html` with your real information:
   - Your full name (hero and footer)
   - Professional title
   - About Me: 2–3 sentences about you, your degree, and what you’re passionate about
   - Skills: your languages, frameworks, and tools
   - Projects: at least one GitHub project with name, description, tech stack, and repo link
   - Education: your degree, institution, expected graduation year
   - Contact: your email and LinkedIn URL

2. **Add your photo** (optional): save your professional photo as `avatar.jpg` in this folder. If the file is missing, the site shows an “Initials” placeholder.

3. **Add a PDF CV** (optional): put a file like `cv.pdf` in the folder and add a link in the Contact section, e.g.  
   `<a href="cv.pdf" download>Download CV (PDF)</a>`

## Hosting on GitHub Pages

1. Create a new repository named **`yourusername.github.io`** (replace `yourusername` with your GitHub username).

2. Push this project to the repo:
   ```bash
   cd developer-portfolio
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. In the repo: **Settings → Pages → Source**: choose **Deploy from a branch**. Branch: **main**, folder: **/ (root)**. Save.

4. Your site will be live at **https://yourusername.github.io** after a few minutes.

## Alternative Hosting

- **Netlify**: Drag and drop this folder at [app.netlify.com/drop](https://app.netlify.com/drop), or connect the GitHub repo.
- **Vercel**: Import the repo at [vercel.com](https://vercel.com); no build step needed for plain HTML/CSS/JS.

## Structure

- `index.html` — Single page with sections: Hero, About Me, Skills, Projects, Education, Contact.
- `styles.css` — Layout, typography, responsive design, dark mode (follows system preference).
- `script.js` — Footer year, mobile menu toggle.

All important text is real HTML (no text in images), with clear section headings for ATS. The site is mobile-responsive and uses standard fonts (Inter).
