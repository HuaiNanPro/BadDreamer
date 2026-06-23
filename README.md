# BadDreamer

This repository hosts the project page and release materials for:

**BadDreamer: Transferable Backdoor Attacks against Video World Models for Autonomous Driving**

Authors: Zhe Shuai, Xiaopeng Xie, Yikun Zeng

## Project Page

The website is in `docs/` and is ready for GitHub Pages.

Local preview:

```bash
python -m http.server 8000 --directory docs
```

Then open <http://localhost:8000>.

## Before Publishing

The Paper button in `docs/index.html` points to <https://arxiv.org/abs/2606.21172>.

Then enable GitHub Pages:

1. Create a GitHub repository named `BadDreamer`.
2. Push this repository to GitHub.
3. In GitHub, open `Settings` -> `Pages`.
4. Set source to `Deploy from a branch`.
5. Select branch `main` and folder `/docs`.

## Contents

- `docs/index.html`: project page
- `docs/styles.css`: page styling
- `docs/assets/figures/`: rendered paper figures for the page
- `docs/assets/paper/baddreamer_arxiv_source.zip`: arXiv source package
- `docs/assets/paper/main.tex`: arXiv-ready LaTeX source
- `docs/assets/paper/ref.bib`: bibliography

## Citation

```bibtex
@misc{shuai2026baddreamer,
  title        = {BadDreamer: Transferable Backdoor Attacks against Video World Models for Autonomous Driving},
  author       = {Shuai, Zhe and Xie, Xiaopeng and Zeng, Yikun},
  year         = {2026},
  eprint       = {2606.21172},
  archivePrefix = {arXiv}
}
```
