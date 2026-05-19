# SAGE: Point Cloud as a Foreign Language for Multi-modal Large Language Model

Project page for the paper *"Point Cloud as a Foreign Language for Multi-modal Large Language Model"* by Sneha Paul, Zachary Patterson, and Nizar Bouguila.

- **Live page** (once deployed): https://snehaputul.github.io/encoder-free-3d/
- **Code**: https://github.com/snehaputul/SAGE3D
- **Paper**: see `Encoder_free_3D.pdf`

## To deploy

1. Create a new GitHub repo named `encoder-free-3d` under your account.
2. Push this directory to that repo's `main` branch.
3. In the repo's **Settings → Pages**, set Source = `Deploy from a branch`, Branch = `main`, Folder = `/ (root)`.
4. Site goes live at `https://snehaputul.github.io/encoder-free-3d/` within ~1 minute.

## To finish the page

The page renders placeholders where images are missing. Add these files under `img/`:

- `img/teaser.png` — Figure 1 (overview / example conversation)
- `img/architecture.png` — Figure 2 (model architecture)
- `img/training.png` — Figure 3 (three-stage training pipeline)
- `img/results.png` — results table or qualitative examples

Once added, the placeholders disappear automatically.

## To update

Edit `index.html` or `css/style.css`, commit, and push. GitHub Pages auto-redeploys.

## Things to update before launch

- Replace the placeholder arXiv link (`#` in `id="arxiv-btn"`) with the real arXiv URL once available.
- Update the BibTeX entry with the correct venue once accepted.
