# IdleOn miniToolBox

**Live page: https://stimdesu.github.io/idleon-minitoolbox/** (prototype)

One header for my small Legends of Idleon tools:

| Tool | Repository |
|---|---|
| Craft Planner: anvil crafts, materials, forge smelting | [idleon-craft-planner](https://github.com/StimDesu/idleon-craft-planner) |
| Cooking Planner: kitchen speed breakdown, meal leveling plan, recipe discovery | [idleon-cooking-planner](https://github.com/StimDesu/idleon-cooking-planner) |
| Stat Finder: every bonus source of a stat, with values from your save | [idleon-stat-finder](https://github.com/StimDesu/idleon-stat-finder) |
| Cogtimizer: construction cog board optimizer | [cogtimizer](https://github.com/StimDesu/cogtimizer) |
| Lab Route: World 4 Laboratory placement | [idleon-lab-route](https://github.com/StimDesu/idleon-lab-route) |
| Star Chart: constellations per character | [idleon-star-chart](https://github.com/StimDesu/idleon-star-chart) |
| Russian translation (Steam mod, link only) | [IdleOn-Rusificator](https://github.com/StimDesu/IdleOn-Rusificator) |

## How it works

- The account (IdleOn Efficiency username or raw save JSON) and the language are set once in the header and kept in this browser.
- Each tool opens in a frame from its own GitHub Pages site. All of them live on `stimdesu.github.io`, so the hub can reach into the tool page: it hides the tool's own header, fills in the username or save and switches the language. Nothing in the tool repositories had to change.
- Opened from anywhere else (a local file, another host) the tools still open but keep their own header and input.
- The tools stay independent: each keeps its repository, build and URL.

Static page, no build step: `index.html` and the icons in `img/` (from the game files; Legends of Idleon and its art belong to Lavaflame2).
