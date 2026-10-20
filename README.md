# Gaurav Harsha

Personal academic portfolio built with Hugo and the `hugo-profile` theme submodule.

Run `hugo server` to preview at http://localhost:1313/. Production deployment runs on pushes to `main`; review changes in a branch and pull request first.

Content sources:

- `hugo.yaml`: biography, appointment, education, software, and navigation.
- `content/publications.md`: publication records and structured citation fields. BibTeX downloads are generated from these fields during the Hugo build.
- `data/news.json`: shared homepage news and archive. Dates sort newest first; only months are displayed. For events documented only to the month, day `01` is a sorting placeholder.
- `layouts/partials/sections/research.html`: research summaries, your thermal proposal figure, and temporary conceptual SVG schematics for topology and disorder.
- `content/cv.md`: teaching, mentoring, honors, and service.
- `static/images/research/thermal-cc.png`: unchanged figure from `CVResume/statements/figs/fig2_thermal_cc.png`.
- `static/files/Gaurav_Harsha_CV.pdf`: neutral website CV copied from `../../JobApps/CVResume/pdf/cv_academia.pdf`. Preserve this stable public URL when refreshing the PDF. The older June PDF remains available for existing links.

Keep project customizations in the root layouts and static directories rather than changing the theme submodule.

The industry download at `static/files/Gaurav_Harsha_Resume.pdf` comes from `../../JobApps/CVResume/pdf/resume_industry.pdf`. Page descriptions live in the page front matter; the default social preview uses the existing portrait configured under `params.images`.
