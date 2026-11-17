EXPERIMENT 10 — DEPLOYING WITH GITHUB PAGES AND NETLIFY
1. Create a GitHub repository named anshu-web-lab (or another available name).
2. Open Terminal in this folder and run:
   git init
   git branch -M main
   git add .
   git commit -m "Initial website"
   git remote add origin https://github.com/YOUR-USERNAME/anshu-web-lab.git
   git push -u origin main
   Replace YOUR-USERNAME with your real GitHub username. If asked, sign in/authenticate with GitHub.
3. GitHub: repository > Settings > Pages > Deploy from a branch > main > /(root) > Save. Wait for the Pages URL to appear.
4. Netlify: sign in at https://app.netlify.com/ using GitHub > Add new site / Import an existing project > choose the repository > leave build command blank and publish directory as / (root) > Deploy.
5. Edit a sentence in index.html, then git add ., git commit -m "Update website", git push. Wait for both deployments and refresh their URLs.
6. Add your actual GitHub Pages and Netlify URLs below and capture screenshots after verifying them.
GitHub Pages URL: ______________________________________
Netlify URL: ___________________________________________

Do not invent deployment URLs. They are created only after publishing from your own accounts.
