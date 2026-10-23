# Single Cell Tutorials

This repository documents single-cell (and spatial transcriptomics) pipeline runs executed locally in Jupyter. Each tutorial is a self-contained HTML report produced by `nbconvert` or Jupyter's "File → Save as HTML", so you can open it directly in the browser without installing anything.

## Structure

- `index.html` — landing page with an index and short summaries of every tutorial.
- `tutorials/` — one HTML file per executed pipeline run.

## How to use

1. Open `index.html` in any browser.
2. Click a tutorial link to view its full HTML report.
3. As new local runs finish, drop the new `.html` into `tutorials/` and add an entry to `index.html`.

## Adding a new tutorial

1. Run your pipeline locally in Jupyter.
2. Save the notebook as HTML (`File → Save and Export → HTML`).
3. Copy the `.html` into `tutorials/`.
4. Add a list item with a link and a one-paragraph summary to `index.html`.
5. Commit and push:

   ```bash
   git add tutorials/your-file.html index.html README.md
   git commit -m "docs(tutorials): add <name> HTML report"
   git push
   ```

## License

MIT