# DECKX — Open Learning Prototype

Built for Ace of Spades. A black-and-white resource discovery website: no authentication, database, API keys, framework, package installation or build step.

## Files
- `index.html` — page and layout
- `style.css` — responsive design, glass surfaces and interactions
- `script.js` — resources, learning decks, filters, dialogs and local bookmarks

## Run on your laptop
Extract this folder and open `index.html` in a modern browser. Keep all three files together. For consistent browser storage behaviour, use a static web server if available, e.g. `python -m http.server 3000`, then visit `http://localhost:3000`.

The interface itself needs no external libraries, fonts or image downloads. Following a resource link requires internet access.

## Put it online
An easy option is Netlify's manual/drag-and-drop deployment:
1. Extract the downloaded ZIP.
2. Sign into Netlify and select its manual deployment / drag-and-drop option.
3. Drop the folder containing `index.html`, `style.css` and `script.js`.
4. Open the assigned site URL and test the resource links on your phone.

Use a free static-hosting plan subject to the host's current limits and terms. A hosting account may be required for you; visitors do not need an account. There is no build command or backend to configure. This project has not been deployed to your own hosting account automatically. The Arena live preview is a development preview, not permanent hosting.

## Working features
- Nine credited resource links: MIT OCW, OSSU, USACO Guide, csdiy.wiki, CS50x, The Odin Project, freeCodeCamp, Full Stack Open and CSES.
- Resource search, category filters and empty states.
- Bookmarks saved to localStorage in the current browser, with in-memory fallback when storage is unavailable.
- Three learning-deck dialogs with suggested steps and a first milestone.
- Mobile layout, keyboard-accessible controls, native dialogs, reduced-motion support.
- Press `/` to focus search; Escape closes a dialog.

## Deliberately not included
No login, user tracking scripts, coding-profile fetching, rating tags, shared forums, chat, cloud sync or course hosting. Those are future product features, not functions to claim in the demo. Resource access, optional certificates, licences and policies belong to the original providers. DECKX is not affiliated with them.

## Editing
Change the `resources` array and `decks` object in `script.js`. Resource ids connect deck steps to the original links. This is hand-curated public data, not an API integration.

## Privacy
Bookmarks stay in this browser and disappear when site data is cleared. There are no analytics scripts. External course sites and your hosting provider have their own logging and privacy policies.

## Suggested judge walkthrough (60 seconds)
1. Explain the problem: good CS resources exist, but choosing a starting point can be overwhelming.
2. Search for OSSU or filter Algorithms; open a resource at its original source.
3. Bookmark USACO Guide and show Saved.
4. Open a learning deck and explain its suggested order and first task.
5. State honestly: this prototype validates discovery and navigation. Platform tags and deck forums are proposed next steps.
