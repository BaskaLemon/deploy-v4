# Portfolio v4 — single-file deploy

Everything is inlined into `index.html`. No build step.

## Vercel
1. `npx vercel login` (first time only)
2. From inside this folder: `npx vercel --prod`
3. Prompts: link to existing project → **N** · directory → Enter · modify settings → **N**

## Netlify
Drag this folder onto https://app.netlify.com/drop

## GitHub Pages
Commit `index.html` to the repo root, then Settings → Pages → deploy from branch.

Needs internet at runtime for: live GitHub contributions and the Motion animation library.
