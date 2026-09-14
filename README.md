# Guanghui Liu - GitHub Pages Portfolio Update

This package updates the computational biology / bioinformatics portfolio with recruiter-facing technical evidence.

## New portfolio evidence

A new **Portfolio Evidence · Flagship Case Studies** section presents three complementary capabilities:

1. **FASTQ processing and quantification workflow** — workflow-demo evidence for paired-end FASTQ QC, preprocessing, and quantification handoff.
2. **Bulk RNA-seq / TCGA BRCA predictive modeling** — links to a portfolio-clean scientific report covering QC, leakage-aware feature discovery, repeated/nested CV, model comparison, holdout evaluation, interpretation, and reproducibility details.
3. **Sample-aware single-cell RNA-seq** — links to a portfolio-clean scientific report covering QC, clustering, annotation, composition, pseudobulk, experimental-unit resolution, and replicate-aware inference boundaries.

The two public reports are stored at:

- `assets/reports/BRCA_integrated_report_portfolio_clean.pdf`
- `assets/reports/scRNA_scientific_report_portfolio_clean.pdf`

The reports intentionally omit or anonymize internal project/session identifiers, dataset record IDs, cryptographic hashes, local/internal paths, and unnecessary sample/subject identifiers while preserving methods, parameters, figures, numerical results, statistical boundaries, and reproducibility software versions.

## Existing workflow demos preserved

The homepage keeps the three workflow demonstrations using the existing repository asset paths:

- `assets/video/fastq.mp4` + `assets/img/demos/fastq-poster.jpg`
- `assets/video/bulk.mp4` + `assets/img/demos/bulk-poster.jpg`
- `assets/video/scrna.mp4` + `assets/img/demos/scrna-poster.jpg`

These video/poster files were not present in the uploaded ZIP used for this edit, so they are referenced but not duplicated in this package. When copying the update into the live repository, **do not delete the existing `assets/video/` or `assets/img/demos/` folders**.

## Additional homepage changes

- Added `Workflow Demos` and `Case Studies` to the main navigation.
- Changed the primary hero CTA to `View demos & reports`.
- Added FASTQ, bulk RNA-seq, scRNA-seq, pseudobulk, and sample-aware inference language to the public technical positioning.
- Strengthened the Bioinformatics toolkit description to reflect implemented bulk and single-cell workflows.
- Removed the initials/avatar graphic from the profile card so the portfolio remains content-first.

## Publish

Copy the contents of this package into the root of `lgh025.github.io`, preserving any newer assets already in the repository that are not present in this package (for example existing workflow-video files). Then:

```bash
git add index.html assets README.md
git commit -m "Add portfolio-clean BRCA and scRNA case-study reports"
git push origin main
```

GitHub Pages should redeploy automatically from `main` / root.

## Direct portfolio report links

- [BRCA portfolio-clean scientific report](assets/reports/BRCA_integrated_report_portfolio_clean.pdf)
- [scRNA portfolio-clean scientific report](assets/reports/scRNA_scientific_report_portfolio_clean.pdf)

On the homepage, the **Bulk RNA-seq** and **Single-cell RNA-seq** demo cards show **View PDF** and **Download PDF** immediately below each video. The same report links are also retained in **Case Studies**. Text contrast across Case Studies and the rest of the site has been strengthened for easier reading.

