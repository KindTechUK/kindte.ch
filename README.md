# kindte.ch

The Kindtech website: one static page that lists every Kindtech project, shows
the analyses of Kindtech Evidence, and says how data is handled, how the work
is paid for and how to contribute. It is served by GitHub Pages at
[kindte.ch](https://kindte.ch).

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
- `assets/`: the pictures. The two maps of reach are drawn by the
  uk-open-data package on real places with an invented charity's counts.
  The others come from the page that runs the analyses, on invented places.
- `CNAME`: tells GitHub Pages the site's address. Leave it as it is.

## Changing it

Read [AGENTS.md](AGENTS.md) first. The short version: no build step, nothing
loaded from other sites, plain words, and keep the list of projects in step
with the organisation page. To contribute to Kindtech's tools, see the
[contributing guide](https://github.com/KindTechUK/.github/blob/main/CONTRIBUTING.md).
