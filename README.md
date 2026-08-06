# ai_assets

Static image assets, referenced by external documents via raw URLs.

## Layout

```
<set>/<doc-slug>/<NN>.<ext>
e.g. 14_easy/3_1_cnn_fine_tuning/07.png
```

Files are numbered in order of appearance within each document.

## URL scheme

```
https://raw.githubusercontent.com/withSG/ai_assets/master/<set>/<doc-slug>/<NN>.<ext>
```

## Notes

- Treat published files as immutable: overwriting a file silently changes every
  document that references it. Add a new number instead, unless an in-place
  replacement is intended.
- This repository must stay public for raw URLs to work.
