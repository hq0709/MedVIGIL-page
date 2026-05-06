# MedVIGIL — Project Page

Static project landing page for the MedVIGIL benchmark (preprint, under review).

**Live site:** https://hq0709.github.io/MedVIGIL-page

## Related resources

| Resource | Link |
|---|---|
| Benchmark dataset | https://huggingface.co/datasets/jhq0709/MedVIGIL |

## Local preview

```bash
git clone https://github.com/hq0709/MedVIGIL-page.git
cd MedVIGIL-page
python3 -m http.server 8000
# open http://localhost:8000
```

The page is a single static `index.html` with inline CSS — no build step needed. Figures live under `static/images/`.

## License

Page source under MIT. Embedded figures inherit the licence of the parent paper.
