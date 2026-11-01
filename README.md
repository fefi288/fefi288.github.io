# Fernando Toro — Engineering Portfolio

A static portfolio site containing **Introduction → Experience → Projects**, with four interactive CAD galleries.

## Preview
Double-click `index.html` while the `assets/` directory is alongside it. No development server or framework is required. A self-contained `Fernando_Toro_Portfolio_Updated.html` preview is also provided separately.

## Publish with GitHub Pages
1. Create a GitHub repository named `<your-github-username>.github.io` (or any repository name for a project-based URL).
2. Upload the contents of this folder, **including** `index.html` and the entire `assets/` folder, to the repository root.
3. In the GitHub repo, go to **Settings → Pages**, and select **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Once published, open your GitHub Pages website and verify all project galleries work.

## Update content
- Edit the introduction and experience text directly in `index.html`.
- Each project card appears in the `.project-grid` section.
- Project gallery labels and detailed paragraphs are in the `PROJECTS` JavaScript object near the bottom of `index.html`.
- Add new screenshots to `assets/` and add them to that project’s gallery array.
- The website uses one fixed red accent palette, defined in the `:root` CSS variables at the top of `index.html`. No color switcher.

## Present status
All projects are in progress. Performance calculations, CFD, FEA, prototypes, and validation data are **not** claimed. Turbine details describe design intent and future fluid-dynamics work, not demonstrated system performance.

Engine project update: the eventual goal is diesel compression-ignition operation, with compressed-air mechanism testing first. Bore, stroke, clearance volume, and compression ratio are not yet validated.
