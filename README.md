# Academic Portfolio Website

A classic, typographically refined academic website for a Mathematics & Data Science researcher.

## Files

- `index.html` — main site (self-contained, no build step needed)
- `cv.pdf` — add your CV here (the "Download CV" button links to this)

## Deploying to GitHub Pages

1. **Create a new repository** on GitHub named `yourusername.github.io`
   (replace `yourusername` with your actual GitHub username)

2. **Upload your files:**
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial site"
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository → Settings → Pages
   - Under "Source", select `main` branch and `/ (root)` folder
   - Click Save

4. Your site will be live at `https://yourusername.github.io` within a few minutes.

## Customizing the Site

Search for these placeholders in `index.html` and replace them:

| Placeholder | Replace with |
|---|---|
| `Dr. Your Name` | Your full name |
| `YN` | Your initials |
| `you@university.edu` | Your email |
| `University Name` | Your institution |
| `Associate Professor` | Your actual title |
| Publication entries | Your real publications |
| Course entries | Your actual courses |
| CV entries | Your real positions & awards |

## Adding a Custom Domain (optional)

1. Buy a domain (e.g. `yourname.com`)
2. In your repo, create a file named `CNAME` containing just your domain: `yourname.com`
3. Configure DNS at your registrar to point to GitHub Pages (see GitHub docs)
