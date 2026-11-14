# Pokémon ROM Hack Guides

Searchable reference guides for Pokémon ROM hacks, built to look things up while you play. Static site on GitHub Pages: https://veturian.github.io/pokemon/

## What's here

- `index.html` – the hub. A card for every hack, with search (name, base game or feature), sorting, card and list layouts, filter chips, a random-hack button, and a light/dark toggle. It also has a "What's new" panel and a "Requests & questions" link that opens a GitHub issue.
- `<hack>/index.html` – one folder per hack, each a single self-contained page. Most have a **Pokédex** tab and a **Wild Encounters** tab; Emerald Adventure currently has Wild Encounters.
- `updates.json` – the entries and hack list behind the "What's new" panel.
- `og.png` – the image shown when a link to the site is pasted into Discord, texts and similar.

## Hacks covered

Bill's Secret Garden DX, Brisk Emerald, Ceruleum, Classic, Crestfall, Crystal Inheritance, Elysium, Emerald Adventure, Phoenix Red, RiverTeal, R.O.W.E., Silver Mirror.

## Updating the "What's new" log

The panel reads `updates.json`. With a fine-grained GitHub token that has **Contents: Read and write** on this repo, the page can add entries itself; the token stays in that browser only. Without a token the panel is read-only.

## Requests and questions

Open an issue on this repo: https://github.com/veturian/pokemon/issues

## Related

[ROM Log](https://veturian.github.io/romlog/) – a personal log of the hacks and fan games I've played. It's a separate project and doesn't share data with these guides.
