# Poster uploads

Add poster PDFs to this folder with short, stable names, for example:

- `esmo-ai-2026-9p.pdf`
- `esmo-ai-2026-10p.pdf`
- `sabcs-2026-2118.pdf`

Then add a `pdf` field to the corresponding entry in `_data/research_outputs.yml`:

```yaml
pdf: "/files/posters/esmo-ai-2026-9p.pdf"
```

For a visual card, also add a 16:9 preview image under `images/posters/` and set:

```yaml
thumbnail: "/images/posters/esmo-ai-2026-9p.jpg"
```

The public poster card will show the preview and an “Open poster PDF” link.
