# kindte.ch

The Kindtech website: one static page that says what the lenses are, how data
is handled, the ways to use the tools, what is open source and how to
contribute. It is served by GitHub Pages at [kindte.ch](https://kindte.ch).

## Look at it on your own machine

There is nothing to install. Open `index.html` in a browser, or serve the
folder:

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## What is here

- `index.html`: the whole page, with its styles. Every outside address it
  links to is listed in the comment at the top of the file.
- `assets/`: the pictures. They come from the lens page running on invented
  data.
- `CNAME`: tells GitHub Pages the site's address. Leave it as it is.

## Changing it

Read [AGENTS.md](AGENTS.md) first. The short version: no build step, nothing
loaded from other sites, plain words, and keep the "Open source" section in
step with the organisation page. To contribute to Kindtech's tools, see the
[contributing guide](https://github.com/KindTechUK/.github/blob/main/CONTRIBUTING.md).
