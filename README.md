# Personal research page — Matthieu Branthôme

Source of the personal research page hosted on the IRISA web space:
<https://people.irisa.fr/Matthieu.Branthome>

Matthieu Branthôme is an Associate Professor in Computer Science at the University of
Rennes (IUT Lannion), affiliated with the [IRISA](https://www.irisa.fr/) laboratory,
BARD team. Research topics: AI for education, learning analytics, serious games, and
computer science education.

## What this is

A plain static website. No build step, no framework, no dependencies — the files in this
repository are exactly the files served in production.

| File | Content |
|------|---------|
| `index.html` | Home: biography, research interests, news, contact |
| `research.html` | Research themes, student supervision, scientific responsibilities |
| `publications.html` | Journal, conference and workshop publications |
| `software.html` | Pyrates serious game |
| `teaching.html` | Courses taught at IUT Lannion and ENSSAT Lannion |
| `cv.html` | Positions and education |
| `style.css` | Single stylesheet shared by all pages |
| `photo.jpg` | Portrait |

## Working on it locally

Open `index.html` in a browser. That's the whole workflow — there is nothing to compile
and nothing to install.

## Deployment

The site is deployed to the IRISA personal web space over WebDAV. The files at the root of
this repository are copied as-is to the root of the web space; `index.html` is the entry
point.

## License

Content (text, publication list, portrait) © Matthieu Branthôme, all rights reserved.
The HTML and CSS scaffolding may be reused freely.
