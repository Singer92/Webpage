# Ezhilarasi Murugesan — Carnatic Vocalist

A free, self-contained landing page for Carnatic vocalist and music educator **Ezhilarasi Murugesan**, built to be shared as a single link when seeking performance, teaching, playback singing, and Tamil lyric-writing opportunities.

No ads, no tracking, no backend, no build step. One HTML file.

## What's on the page

- **Hero** — name, lineage, social links, main portrait (placeholder)
- **About** — bio, guru lineage, and dated academic credentials (Kalakshetra, University of Madras, and her Research Scholar standing in Indian Music at Vels Institute of Science, Technology & Advanced Studies)
- **Teaching & Outreach** — her decade-plus music education career across schools and fine arts institutions, including her work with neurodiverse learners and her involvement in the Aanmajothi Music to Schools Project (with T.M. Krishna and her guru, Sangeetha Sivakumar) — each entry has its own photo placeholder
- **Performances** — a timeline of venues and programmes, each with a photo placeholder
- **Beyond the Concert Stage** — her work as an independent artist and songwriter with her band *On The Streets of Chennai* (violin, guitar, vocals), her openness to playback singing, and her published Tamil poems leading into an interest in writing song lyrics for Tamil cinema — with placeholders for live performance and poem-sample images
- **Collaborations** — sabhas, dance academies, and festivals she has worked with
- **Gallery** — an open grid for event photos
- **Connect** — phone, email, WhatsApp, and social icons

## File structure

```
.
├── index.html      # the entire site — HTML, CSS, and JS in one file
└── README.md       # this file
```

> The file in this repo may currently be named `ezhilarasi-murugesan.html`. Rename it to `index.html` before publishing so GitHub Pages serves it as the homepage.

## Publishing it for free (GitHub Pages)

1. Create a new GitHub repository (e.g. `ezhilarasi-murugesan`).
2. Upload `index.html` (and this `README.md`) to the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then **Save**.
6. Wait a minute or two — GitHub will give you a live link, typically:
   `https://<your-username>.github.io/<repo-name>/`

That link is what you share with sabhas, schools, directors, music directors, or production teams.

## Updating content

Everything lives in plain HTML — no install, no command line required.

### Adding photos

Search the file for `photo-frame`, `g-frame`, or `poem-frame` — each is a placeholder box, including one for every entry in the Teaching & Outreach section. Replace its contents with:

```html
<img src="photos/your-photo.jpg" alt="Describe the photo here">
```

Create a `photos` folder in the repo and upload images there, then point `src` to `photos/filename.jpg`.

### Adding social links

Find the three `<a href="#" aria-label="Instagram" ...>` (and YouTube, Facebook) blocks — there are two sets, one in the hero and one in the Connect section. Replace `href="#"` with the real profile URL.

### Adding poem links

In the **Lyric Writing** card under "Beyond the Concert Stage," replace the two `href="#"` links ("Her poems on Instagram" / "Her poems on YouTube") with direct links to the actual posts.

### Editing text

All copy is plain text inside the HTML — open the file in any text editor, find the section, and edit directly.

## License

This site was built for Ezhilarasi Murugesan's personal use. No external licensing restrictions apply to the code itself; reuse or adapt freely.
