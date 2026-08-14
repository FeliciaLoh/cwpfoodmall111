[README.md](https://github.com/user-attachments/files/31051020/README.md)
# Causeway Point — Food Directory

A single-page food directory for Causeway Point, styled like a mall directory board: floor filters (B1, 02, 03, 04), split-flap unit tags, search, halal toggle, and a spin-the-wheel picker.

No build step, no dependencies — plain HTML/CSS/JS in `index.html`.

## Deploy: GitHub → Vercel

1. **Create a GitHub repo**
   - Unzip this folder locally.
   - In the unzipped folder, run:
     ```
     git init
     git add .
     git commit -m "Initial commit"
     ```
   - Create a new empty repo on GitHub (no README/gitignore), then:
     ```
     git remote add origin https://github.com/<your-username>/<repo-name>.git
     git branch -M main
     git push -u origin main
     ```

2. **Import into Vercel**
   - Go to [vercel.com/new](https://vercel.com/new) and sign in with GitHub.
   - Select the repo you just pushed.
   - Framework preset: choose **Other** (plain static site — no build command, no output directory needed).
   - Click **Deploy**.

3. **Done**
   - Vercel gives you a live URL like `your-project.vercel.app`.

Every future `git push` to `main` auto-redeploys.
