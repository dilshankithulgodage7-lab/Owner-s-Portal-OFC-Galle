# Oceanfront Condominiums Galle — Owner Portal

A single-page website that links owners to the condominium's document collections on Google Drive.

## Files

- `index.html` — the whole site (HTML + CSS in one file, no build step)
- `README.md` — this file

## Editing the document links

Open `index.html` and look for the three `<article class="doc">` blocks inside the
`#documents` section. Each one has:

- `<h3>` — the collection name
- `<p>` — the short description
- `<span class="tag">` — the small labels
- `href="https://drive.google.com/drive/folders/..."` — the Drive link

To add a fourth collection, copy one whole `<article class="doc">` block, paste it
below the last one, and change the text and the link.

## Publishing

Hosted with GitHub Pages from the `main` branch, root folder.

## Note on access

The repository and the website are public, so anyone with the address can see the
page and the folder links. The documents themselves stay protected by the sharing
settings on each Google Drive folder. Keep those folders set to specific people,
not "Anyone with the link", unless the contents are meant to be public.
