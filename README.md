# Guanghui Liu - GitHub Pages Portfolio

This package is ready to copy into the root of `lgh025.github.io`.

## Positioning

The homepage is written for computational biology / bioinformatics / biomedical AI / research-software roles. It follows the attached two-page CV and emphasizes reproducible omics research systems, translational transcriptomics, multi-omics modeling, validation discipline, and scientific delivery.

The public homepage does not use the BioFlowStudio product name in its descriptive text. The workflow videos are presented as technical demonstrations supporting the CV rather than as a commercial product pitch.

## Workflow demos added

A new **Bioinformatics Workflow Demonstrations** section is linked from the top navigation and the primary hero button:

- `assets/video/fastq.mp4` - FASTQ processing workflow (1:14)
- `assets/video/bulk.mp4` - bulk RNA-seq analysis workflow (1:07)
- `assets/video/scrna.mp4` - single-cell RNA-seq workflow (1:40)

Each video uses `controls`, `preload="metadata"`, and a static poster image so the page does not automatically stream all three full videos when a recruiter opens it.

Poster images:

- `assets/img/demos/fastq-poster.jpg`
- `assets/img/demos/bulk-poster.jpg`
- `assets/img/demos/scrna-poster.jpg`

## Other targeted changes

- Added `Workflow Demos` to the main navigation.
- Changed the primary homepage CTA to `Watch workflow demos`.
- Added FASTQ, bulk RNA-seq, and scRNA-seq terms to SEO metadata.
- Updated the professional-profile language to connect raw sequencing workflows with modeling, validation, interpretation, and delivery.
- Updated the Omics & Bioinformatics capability card to reflect executable workflow implementation while keeping claims consistent with the CV.
- Kept the downloadable CV at `assets/Guanghui_Liu_Resume.pdf`.

## Publish

1. Back up the current `lgh025.github.io` repository.
2. Copy the contents of this folder into the repository root.
3. Commit and push to `main`.
4. GitHub Pages should redeploy automatically. If needed, verify Settings -> Pages uses `main` and `/ (root)`.

Example:

```bash
cd /path/to/lgh025.github.io
git add index.html assets README.md
git commit -m "Add bioinformatics workflow demos"
git push origin main
```

## Main files

- `index.html` - homepage content, workflow demo section, SEO metadata
- `assets/css/style.css` - responsive desktop/mobile styling
- `assets/js/main.js` - mobile navigation and reveal animation
- `assets/video/` - three MP4 workflow demonstrations
- `assets/img/demos/` - video poster images
- `assets/Guanghui_Liu_Resume.pdf` - downloadable two-page CV
- `.nojekyll` - static GitHub Pages publishing
