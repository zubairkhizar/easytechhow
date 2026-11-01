# EasyTechHow — GitHub Pages deployment
1. Create a GitHub repository (any name, e.g. easytechhow) and upload ALL files in this folder.
2. Repo Settings > Pages > Build and deployment: Deploy from a branch, branch main, folder / (root). Save.
3. Your site will appear at https://<username>.github.io/<repo>/ first, then add the custom domain:
   Repo Settings > Pages > Custom domain: easytechhow.me, Save. The CNAME file is already included.
4. Namecheap DNS for easytechhow.me (Advanced DNS):
   - 4 A records @ -> 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - 1 CNAME www -> <username>.github.io.
   Wait up to 24 hours for DNS, GitHub will then issue HTTPS automatically.
5. After the site is live, submit https://easytechhow.me/sitemap.xml in Google Search Console.
