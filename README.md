# DECKX
### Open resources. Shared progress.

DECKX is a starting point for self-directed computer science learning. It brings trusted courses, community-built curricula and practice resources into one focused interface—helping learners spend less time searching and more time starting.

Built by **Ace of Spades** for **Community Learning Beyond Schools**.

---

## Why DECKX?

Access to learning material is only the beginning. Choosing a starting point, understanding prerequisites and finding a useful next step can be just as difficult.

DECKX organises existing resources into an approachable library and short learning decks. The knowledge stays with its original creators; DECKX helps learners find their way to it.

## Explore

- **Curated library** — discover resources for CS foundations, algorithms and web development.
- **Search and filters** — find a resource by name, topic or learning direction.
- **Learning decks** — follow suggested routes with context, prerequisites and a practical first milestone.
- **Personal bookmarks** — save resources in your browser without creating an account.
- **Direct access** — open courses and materials on their original websites.
- **Responsive interface** — a monochrome glass design built for desktop and mobile, with keyboard controls and reduced-motion support.

### Three starting points

| Deck | Direction |
| --- | --- |
| **Start from zero** | Build programming foundations and explore the wider CS landscape. |
| **Think like a solver** | Develop algorithmic thinking through explanations and practice. |
| **Make something real** | Learn web fundamentals and progress toward practical projects. |

These are suggested routes, not replacement curricula. Learners can choose the resources that fit their experience and goals.

## Resource community

DECKX highlights the work of educators and open-learning communities:

- [MIT OpenCourseWare](https://ocw.mit.edu/)
- [OSSU Computer Science](https://github.com/ossu/computer-science)
- [USACO Guide](https://usaco.guide/)
- [csdiy.wiki](https://csdiy.wiki/en/)
- [Harvard CS50x](https://cs50.harvard.edu/x/)
- [The Odin Project](https://www.theodinproject.com/)
- [freeCodeCamp](https://www.freecodecamp.org/learn/)
- [Full Stack Open](https://fullstackopen.com/en/)
- [CSES Problem Set](https://cses.fi/problemset/)

All linked materials belong to their respective creators. DECKX is an independent project and does not imply affiliation or endorsement. Access conditions, optional paid offerings and licences are determined by each provider.

## Run locally

Download or clone the repository, then open `index.html` in a modern browser.

For local development with consistent browser storage behaviour:

```bash
python -m http.server 3000
```

Open **http://localhost:3000**.

No package installation or build step is required.

## Deploy

DECKX can be deployed on GitHub Pages or another static hosting service.

For GitHub Pages:

1. Keep `index.html`, `style.css` and `script.js` at the repository root.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**, then **main** and **/ (root)**.
4. Save and use the site URL shown after deployment.

## Project structure

```text
index.html   Page structure and interface
style.css    Responsive layout and glass styling
script.js    Resource catalogue, learning decks and interactions
README.md    Project overview and setup
```

To add or update a resource, edit the `resources` array in `script.js`. Learning routes are defined in the `decks` object.

## Design principles

**Credit the source.** Link to original materials rather than republishing them.

**Lower the barrier.** Let learners explore without registration.

**Start with context.** Explain who a resource is for and where it fits.

**Keep it lightweight.** Use native web technologies without runtime framework dependencies.

## Privacy

Bookmarks are stored locally in the current browser and are not synced across devices. Clearing site data removes them. The website includes no analytics scripts; hosting providers and external resource sites have their own privacy practices.

## Next steps

The current release focuses on discovery and guided navigation. Planned extensions include opt-in coding-profile tags and discussion spaces for individual decks, helping learners find peers and work through challenges together.

## Contributing

Suggestions for useful resources, clearer learning routes and accessibility improvements are welcome. Include the original source link, intended audience and a short explanation of where your suggestion fits.

---

**DECKX · Ace of Spades**  
Global knowledge. Learn together. Give back.
