# Food Directories

Two static HTML prototypes:

- `index.html` — landing page linking to both
- `causeway-point.html` — mall directory board for Causeway Point (floor filters, split-flap unit tags, halal toggle, spin-the-wheel picker)
- `woodlands-738094.html` — neighbourhood eatery guide near Woodlands Drive 72 / postal code 738094 (category filters, distance sort, spin-the-wheel picker)

No build step, no dependencies — plain HTML/CSS/JS.

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
   - Framework preset: choose **Other** (it's a plain static site — no build command, no output directory needed).
   - Click **Deploy**.

3. **Done**
   - Vercel gives you a live URL like `your-project.vercel.app`.
   - `/` → landing page
   - `/causeway-point` → Causeway Point directory
   - `/woodlands-738094` → Woodlands directory

Every future `git push` to `main` auto-redeploys.
