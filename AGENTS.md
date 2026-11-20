# kindte.ch development guidelines

For anyone, person or agent, changing this repository. The shared
[contributing guide](https://github.com/KindTechUK/.github/blob/main/CONTRIBUTING.md)
and [AI policy](https://github.com/KindTechUK/.github/blob/main/AI_POLICY.md)
apply here. This file adds what is specific to this repository.

This is the Kindtech website, served by GitHub Pages at kindte.ch. It is one
static page.

## Rules

1. No build step. The site is `index.html`, the pictures in `assets/` and the
   `CNAME` file. Do not add a framework, a bundler or a package file.
2. Nothing is loaded from another site: no analytics, no cookies, no fonts or
   scripts from a CDN. Styles live in the one `<style>` block.
3. Every outside address is listed in the comment at the top of `index.html`.
   When you add or change a link, update that list in the same change. Do not
   link to something that is not live yet.
4. Write for a charity worker: plain words, short sentences, no jargon. Aim
   for WCAG AA: real headings in order, text contrast of at least 4.5 to 1,
   alt text on every picture, and a page that works with a keyboard and
   without JavaScript.
5. Say the same thing as the organisation page. The list of projects follows
   `profile/README.md` in `KindTechUK/.github`. Change both together.
   Names that are about to change are listed in the comment at the top of
   `index.html`, with where each is used.
6. No personal data about real people, and no personal email address. Any
   picture of a result must come from invented data and say so.
7. Do not rename or remove `CNAME`.

## Checks to run before pushing

Open `index.html` in a browser at phone width and at desktop width, and tab
through it with the keyboard. Check that every address in the list at the top
of the file opens.

## Commits and pull requests

- Conventional commit subjects (`feat:`, `fix:`, `docs:`, `chore:`). One
  change per pull request.
- Do not add `Co-authored-by` or other tool trailers to commits. Say in the
  pull request description which AI tools did a meaningful part of the work,
  or write "None".
- Include a screenshot in the pull request for anything a person looks at.
