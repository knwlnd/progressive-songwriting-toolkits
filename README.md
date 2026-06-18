# Modern Progressive MIDI

A dependency-free static catalogue site for progressive metal MIDI products.

## Local preview

Open `index.html` directly, or serve the directory with any static file server:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages

The site uses relative URLs and can be published directly from the repository
root. In the repository settings, set Pages to deploy from the default branch
and `/ (root)`.

## Adding products

Duplicate `products/progressive-songwriting-toolkit.html`, update its content,
and add the new product card or link to `index.html`. Shared visual styles live
in `assets/css/styles.css`.
