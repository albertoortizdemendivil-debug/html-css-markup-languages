# HTML & CSS: Markup Languages (ASIR, first term 2026/27)

Coursework from the *Lenguajes de Marcas* (Markup Languages) module: five small websites, built in order from plain semantic HTML to a six-page Bootstrap site. Each project adds something new to the previous one, so the folders are best read in order.

No frameworks other than Bootstrap in the last project; the only JavaScript is a poster carousel and a form alert.

## Projects

Built between September and October 2026.

| # | Project | What is new compared with the previous one |
| --- | --- | --- |
| 1 | [VIGANews, a local newspaper](./unit-1/01-viganews-newspaper) | Semantic page structure (`header`, `nav`, `main`, `section`, `article`, `footer`), headings, `time`, `abbr`, `blockquote` with `cite`, `figure`/`figcaption`, in-page anchors, an external stylesheet with CSS custom properties, `:hover` states and one `@media` rule |
| 2 | [FO&BA News, a sports site](./unit-1/02-sports-news-site) | From one page to three: relative links between pages and sub-folders, a shared stylesheet, a favicon, `details`, ordered and unordered lists |
| 3 | [My Record Store](./unit-1/03-record-store) | A data table (`caption`, `thead`, `tbody`, `th`, `td`) styled with CSS |
| 4 | [Spider-Man site](./unit-1/04-movie-site-media-forms) | Multimedia (`video`, `audio` with two formats) and a form with `fieldset`, `legend`, `label`, text, colour and checkbox inputs, `select`, `textarea`, submit and reset; layout with flexbox |
| 5 | [Horizon Movies, a cinema site](./unit-2/horizon-movies) | A six-page site built on **Bootstrap 5.3** (grid, containers) plus my own stylesheet with three `@media` rules, a poster carousel in JavaScript, a prices table, a contact form and a team page |

## What is not included

- **Images:** posters, logos, sports photos, screenshots of standings and the stock photos on the team page belong to third parties, so they are replaced with grey placeholders with the same file names and proportions. The layouts stay intact; only the pictures are missing.
- **Video and audio** of the Spider-Man project (trailer and soundtrack). The `<video>` and `<audio>` markup is still there but has nothing to play.
- **Exercise statements** from the course, which are not mine to publish.
- Article texts in the first two projects are adapted from local news; the sources are linked in the pages.

## Notes

- **Forms are front-end only.** There is no server, so nothing is sent or stored. The Spider-Man form just shows an alert, and the Horizon Movies contact form has a `netlify` attribute for when it is hosted there.
- The contact phone, email and team surnames in the sample sites are fictional or shortened.
- Bootstrap is included unmodified under the [MIT licence](https://github.com/twbs/bootstrap/blob/main/LICENSE); its licence header is kept in the file.
- The main file of each project is `index.html`. Open it in a browser, or enable GitHub Pages to see the sites live.

## Author

Alberto Ortiz de Mendivil, ASIR student. More projects: [homelab](https://github.com/albertoortizdemendivil-debug/homelab) and [linux-network-services-lab](https://github.com/albertoortizdemendivil-debug/linux-network-services-lab).
