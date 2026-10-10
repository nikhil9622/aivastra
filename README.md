# Aivastra website

A static, responsive landing page for the early-stage Aivastra SaaS concept.

## Preview locally
Open `index.html` in a browser. No build step or dependencies are required.

## Deploy to Vercel (easiest: GitHub import)
1. Create a GitHub repository named `aivastra-website`.
2. Upload `index.html` and this `README.md` to the repository root.
3. Sign in at https://vercel.com/ with GitHub.
4. Choose **Add New → Project**, import `aivastra-website`, and deploy.
5. In the Vercel project, open **Settings → Domains** and add `aivastra.me` and optionally `www.aivastra.me`.
6. In Namecheap, open **Domain List → Manage → Advanced DNS** and add the DNS records Vercel displays. Do not copy DNS values from an unrelated tutorial.
7. Return to Vercel and wait for verification and HTTPS to complete.

## Before publishing
- The contact button currently uses `hello@aivastra.me`. Set up that mailbox or forwarding in Namecheap first, or replace the address in `index.html` with an email address you can receive.
- Update the copy once Aivastra's actual target users and product direction are defined.
- The website intentionally does not claim existing customers, revenue, product features, or launch dates.

## Updating the site
Edit `index.html` and push the change to GitHub. Vercel will automatically deploy new commits when the repository is connected.
