# Portfolio & learning blog

Plain HTML + CSS. No build step.

```
index.html                 Home / about
projects.html              Project cards
style.css                  All styling (light + dark mode)
blog/index.html            List of posts
blog/building-this-site.html   Your first post (you write it)
```

## Your jobs (the bits worth learning)

1. **Personalise it.** Search every file for `YOUR` and `LANGUAGE` and replace them
   (your name, GitHub username, LinkedIn, email, the language you wrote the
   password checker in). Rewrite the intro on `index.html` in your own words.
2. **Fill in the password checker card** on `projects.html` with what it really
   does and a link to its repo.
3. **Put it on GitHub.** Create a repo named exactly `YOUR-USERNAME.github.io`, then:
   ```
   git init
   git add .
   git commit -m "First version of portfolio site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
   git push -u origin main
   ```
4. **Deploy.** Repo → Settings → Pages → Source: "Deploy from a branch",
   branch `main`, folder `/ (root)`. After a minute it's live at
   `https://YOUR-USERNAME.github.io`.
5. **Write the first post** in `blog/building-this-site.html` (prompts are inside).

## Adding things later

- **New project:** copy a `.card` block in `projects.html`.
- **New post:** copy `blog/building-this-site.html`, rename it, write it, then
  add a card linking to it at the top of `blog/index.html` (and update
  "Latest posts" on the home page).
