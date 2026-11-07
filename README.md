# Runebound Solo Companion

A single-file web app for playing **Runebound, Third Edition** solo with the **Unbreakable Bonds** expansion. You move the miniatures and throw the real tokens; the app runs the enemy's combat board and tracks the rest.

Open `index.html` in any browser, or serve the repo with GitHub Pages. State is saved in the browser's local storage on that device only.

## What it does

- **Combat:** enemy combat boards for Warrior, Mystic, Savage and Trickster, resolved top to bottom, with skipped spaces, passes, a surge helper and an optional digital token caster.
- **Hero:** damage, gold, turn, trophies, quests, rumors and the prepare token.
- **Scenario:** act tracker, scorched earth, a warband tracker for The Locust Swarm, and webs and Queen Ariad for Caught in a Web.
- **Reminders:** solo rules, enemy-turn rules and a short rulings list.

## Sources and caveats

- Rules come from the official [Unbreakable Bonds rules PDF](https://fgbradleys.com/wp-content/uploads/rules/Runebound%20-%20expansion%20-%20Unbreakable%20Bonds.pdf). Check it for exact wording.
- Board text and token faces were read from screenshots of the [Token Caster](https://token-caster.tabletop.kelsam.net/), a fan tool. Compare them with your printed boards and tokens.
- The Locust Swarm text I read lists no separate loss condition, so the app doesn't assume one.
- This is a fan-made tool, not affiliated with Fantasy Flight Games.

See `docs/cheat-sheet.md` for the printable rules summary.
