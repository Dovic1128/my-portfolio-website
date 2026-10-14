# Dovic Sarrondo — Personal Portfolio

A modern, responsive personal portfolio website built with pure HTML and CSS.
No frameworks, no build tools, no dependencies — just two files.

## Files

| File         | Purpose                                      |
| ------------ | -------------------------------------------- |
| `index.html` | All website content and structure            |
| `style.css`  | All styling, layout, animations, and responsive rules |

## How to Preview

1. Open `index.html` in any web browser, **or**
2. Use a local server for hot-reload during development:
   - If you have Python: `python3 -m http.server` then visit `http://localhost:8000`
   - If you have Node: `npx serve` then visit the URL shown in the terminal

## How to Customize

Edit `index.html` and replace all placeholder content:

- **Name**: Replace "Jane Doe" with your name (in the hero, footer, and title)
- **About**: Update the About Me paragraph with your own story
- **Skills**: Change the card titles and descriptions to match your skills
- **Projects**: Replace project names, descriptions, and links with your real projects
- **Contact**: Update email address and social media links (GitHub, LinkedIn, Twitter)
- **Colors**: Edit the CSS variables at the top of `style.css` (`--color-primary`, `--color-accent`, etc.)

## Deploy to GitHub

1. Create a new repository on GitHub
2. In your project folder, run:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio website"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git push -u origin main
   ```

## Deploy to Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with your GitHub account
2. Click "New Project" and import the repository you just pushed
3. Vercel will auto-detect it as a static site — no configuration needed
4. Click "Deploy" — your portfolio will be live in seconds with a free URL

Alternatively, install the Vercel CLI and run `vercel` in the project folder.

## License

Free to use for personal and educational purposes.
