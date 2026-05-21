# CentraleSupélec Report Template

This repository contains a non-official LaTeX report template for CentraleSupélec reports, lab write-ups, project submissions, and similar technical documents.

The template was adapted from an anonymous template that may have been made by past Brazilian students. It is not official school material and does not guarantee compliance with any course, instructor, jury, or academic-year formatting requirement. Use it at your own risk and always check the instructions for the specific report you are submitting.

[Overleaf version available!](link)

If this template saves you time, please leave a ⭐ on the repository.

## What Is Included

- `main.tex`: the report template source.
- `references.bib`: sample BibTeX bibliography entries.
- `figures/`: logo and sample figure assets used by the template.
- `main.pdf`: compiled preview of the template.

The template includes a title page, abstract page, table of contents, main report sections, figures, tables, pseudocode, references, appendices, acknowledgements, and an optional AI-use disclosure note.

## How To Adapt

Edit the report metadata near the top of `main.tex`:

```tex
\newcommand{\reporttitle}{...}
\newcommand{\reportsubtitle}{...}
\newcommand{\reportauthors}{...}
\newcommand{\reportaffiliation}{...}
\newcommand{\reportsupervisors}{...}
\newcommand{\reportdate}{...}
```

Replace the placeholder text, sample table, sample figure, and sample bibliography entries with material for your report. Add all cited sources to `references.bib`, keeping a consistent bibliography style and level of detail.

For French reports, uncomment the French `babel` package line in `main.tex`.

To remove the AI-use disclosure note, comment out the `\aidisclosure` line near the end of the main content.

## License And Reuse

See [LICENSE](LICENSE). The source notice at the top of `main.tex` must remain in every copy or derivative version. The template may be used, adapted, and distributed in any way as long as that notice is kept.
