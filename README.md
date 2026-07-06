# My Portfolio

A simple, personal writer portfolio. Plain HTML and CSS — no build tools, no installs required.

## 1. Edit your content

Open `index.html` in any text editor (even Notepad or TextEdit works, but a free tool
like [VS Code](https://code.visualstudio.com/) makes this much easier).

Look for comments like this — everything between them is yours to change:

```html
<!-- EDIT: your bio -->
...replace this text...
<!-- /EDIT -->
```

Your name, contact info, experience, skills, achievements, and languages are
already filled in from your CV. Two things your CV template left blank still
need your input — search for `[University Name]` and `[year]` inside
`index.html` (in the Background section) and replace them with your real
details.

Anything else you want to update later:
- Add a new role by duplicating the `.piece` block in the Experience section
- Add more skills by duplicating a `<li>` in the Skills section
- Fill in a completed certification, or delete the "(optional...)" tag once you've added the real date
- Your email/phone in Contact

You don't need to touch `style.css` or `script.js` unless you want to change colors or fonts.

## 2. Put it on GitHub

1. Create a free account at [github.com](https://github.com) if you don't have one.
2. Click the **+** in the top right → **New repository**.
3. Name it something like `portfolio`, keep it Public, and click **Create repository**.
4. On the next page, use the **"uploading an existing file"** link and drag in
   `index.html`, `style.css`, and `script.js`.
5. Scroll down and click **Commit changes**.

(If you're comfortable with the command line later, you can also use `git push` —
but the drag-and-drop upload works perfectly fine for this.)

## 3. Deploy it on Vercel

1. Create a free account at [vercel.com](https://vercel.com) and sign in **with your GitHub account** — this connects the two automatically.
2. Click **Add New → Project**.
3. Find your `portfolio` repository in the list and click **Import**.
4. Vercel will detect it's a static site — you don't need to change any settings.
5. Click **Deploy**.

In about 30 seconds, Vercel gives you a live URL like `portfolio-yourname.vercel.app`.

## 4. Update it later

Whenever you want to add a new piece of writing or change your bio:
1. Edit the file on GitHub directly (click the file → pencil icon → edit → commit), or edit locally and re-upload.
2. Vercel automatically redeploys within seconds of any change to the repository — no extra steps needed.

That's the whole loop: **edit → commit → Vercel updates itself.**
