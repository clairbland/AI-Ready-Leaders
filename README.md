# AI Ready Leaders: interactive courses

Four interactive modules for senior and new leaders at Harbourline, a fictional financial services firm. Ready to publish free on GitHub Pages.

| Module | File |
| --- | --- |
| 1. Leading the AI Shift | `courses/1-leading-the-ai-shift.html` |
| 2. The Delegation Edge | `courses/2-the-delegation-edge.html` |
| 3. Conversations That Count | `courses/3-conversations-that-count.html` |
| 4. Trust, But Verify | `courses/4-trust-but-verify.html` |

`index.html` is the landing page that lists all four modules. Each module has a "Back to all modules" link in its footer.

## Publish on GitHub Pages

1. Sign in to GitHub (or create a free account) and select **New repository**.
2. Name it, for example `ai-ready-leaders`. Make it **Public**, then select **Create repository**.
3. On the new repository page, select **uploading an existing file**.
4. Unzip this package on your computer. Open the folder and drag **everything inside it** into the upload area: `index.html`, `README.md`, `.nojekyll`, and the `assets` and `courses` folders. Upload the contents, not the zip file or the outer folder.
   - The `.nojekyll` file may be hidden on your computer. If you can't see it, it's fine to leave it out.
5. Select **Commit changes**.
6. Go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main** and folder to **/ (root)**, then select **Save**.
7. After a minute or two, your site is live at:
   `https://YOUR-USERNAME.github.io/ai-ready-leaders/`

## Link it from Wix

- On your Wix portfolio page, add a button such as **Try the AI Ready Leaders courses** and link it to your GitHub Pages address. Set it to open in a new tab.
- To link straight to one module, add its path, for example:
  `https://YOUR-USERNAME.github.io/ai-ready-leaders/courses/1-leading-the-ai-shift.html`

## Add your back link

Open `index.html` on GitHub (select the file, then the pencil icon), find this line near the bottom and replace the address with your Wix portfolio page:

```
const PORTFOLIO_URL = "https://your-site.wixsite.com/portfolio";
```

Until you change it, the "Back to my portfolio" links stay hidden.

## Good to know

- **Progress and passport.** Modules save progress in the visitor's browser, and the programme passport fills in as they complete each module.
- **Updating a module.** Upload a new version of the file to the `courses` folder with the same name, and GitHub Pages updates within a few minutes.
