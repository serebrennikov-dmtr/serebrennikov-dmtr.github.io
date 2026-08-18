# Publication figures

Thumbnails shown beside entries on the Publications page. Optional — an entry
without one renders as a full-width text row, so partial coverage is fine.

## Adding one

1. Drop the image here, named after the paper, e.g. `near-repeat-almaty.png`.
2. Add two lines to the entry in `data/articles.yml` (or `preprints.yml` /
   `reports.yml`):

```yaml
  thumbnail: assets/figures/pubs/near-repeat-almaty.png
  thumbnailAlt: "Knox test results for theft in Almaty"
```

`thumbnailAlt` is what a screen reader announces — describe what the figure
shows, not that it is a figure.

## What to supply

Displayed at 132px wide, so export at roughly 400–600px wide for retina.
White or transparent background both work: the page is `#FAF9F7`, close
enough to white that an opaque white plot does not read as a pasted rectangle.

Figures must be **real figures from the work**, not decorative stand-ins.
Where the analysis has public code — as with
`Surveillance-as-Governance.Paper-Repo` — regenerating the plot from that code
gives better resolution than cropping the publisher PDF, and avoids the
question of what rights were transferred to Elsevier or Springer.
