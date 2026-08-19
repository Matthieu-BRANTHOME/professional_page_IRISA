# Personal research page — Matthieu Branthôme

Source of the personal research page hosted on the IRISA web space:
<http://people.irisa.fr/Matthieu.Branthome>

Matthieu Branthôme is an Associate Professor in Computer Science at the University of
Rennes (IUT Lannion), and a member of the [BARD](https://www-bard.irisa.fr/) team of the
[IRISA](https://www.irisa.fr/) laboratory. Research topics: AI for education, learning
analytics, serious games, and computer science education.

## What this is

A plain static website. No build step, no framework, no dependencies — the files in this
repository are exactly the files served in production.

| File | Content |
|------|---------|
| `index.html` | Home: short biography, research interests, contact, news |
| `cv.html` | Professional experiences and education |
| `research.html` | Reviewing, organizing committees, workshops, student supervision, responsibilities, awards, science popularization |
| `publications.html` | Journal, conference and workshop publications, with DOI and HAL links |
| `software.html` | The Pyrates serious game |
| `teaching.html` | Courses taught at IUT Lannion and ENSSAT Lannion |
| `style.css` | Single stylesheet shared by every page |
| `photo.jpg` | Portrait |
| `pyrates.png` | Pyrates screenshot, used on the Software page |
| `favicon.png` | IRISA logo, used as the browser tab icon |

## Conventions

- **English** throughout.
- Internal navigation stays in the page; **every external link opens in a new tab**
  (`target="_blank" rel="noopener"`).
- No JavaScript. The collapsible news archive on the home page uses the native HTML
  `<details>` element, so the site works on a plain file-serving web space.
- The footer of each page carries a `Last updated:` line — worth refreshing when the
  content changes.

## Working on it locally

Open `index.html` in a browser. That is the whole workflow: nothing to compile, nothing to
install. For a closer match to production, serve the folder over HTTP:

```sh
python3 -m http.server 8000
```

## Deployment

The site is deployed to the IRISA personal web space over WebDAV. The files at the root of
this repository are copied as-is to the root of the web space; `index.html` is the entry
point. The deployment script and the WebDAV credentials are kept outside this repository.

## License

Content (text, publication list, portrait, screenshot) © Matthieu Branthôme, all rights
reserved. The HTML and CSS scaffolding may be reused freely.
