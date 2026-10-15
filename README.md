[README.md](https://github.com/user-attachments/files/33473086/README.md)
# Bottom Time 3D

A New Zealand spearfishing and freediving game in real-time 3D in the browser. It opens on a map of New Zealand with four famous dive sites. Pick one and dive it: freedive or scuba, hunt down the barrel of your speargun, watch for dolphins, orca and gannet work-ups, and weigh in under the real recreational rules.

## The four sites

- **Goat Island** (Leigh): New Zealand's first marine reserve, with the open reef either side of it.
- **Tūhua / Mayor Island** (Bay of Plenty): a sleeping volcano with hot springs and Two Fathom Reef. Kingfish and work-ups.
- **Kaikōura** (Canterbury): cold green water under the mountains, kelp, crays, blue cod and dusky dolphins.
- **Fiordland** (Doubtful Sound): a sheer wall under a tea-coloured fresh-water layer, black coral, blue cod and the resident bottlenose dolphins.

Travelling to another site reloads the game and builds the new coast, which takes a few seconds.

## Prize money and the dive shop

Every weigh-in pays club prize money: half a dollar for each point you score (selling a recreational catch is illegal in New Zealand, so the money is competition prizes, not fish sales). The club also pays one-off bounties for milestones, such as your first legal kingfish or ten species landed.

Spend it in the dive shop, open from the menu, the weigh-in or the map. Your gear goes with you to every site, and most of it can be switched on or off before a dive.

- **Spearguns and tips**: the 1.1 m all-rounder, the 1.4 m bluewater gun, double floppers and slip tips.
- **Rigging**: flasher, extra band, loading pad (faster reloads), gun reel (more line for running fish), breakaway rig, and a burley pot (burley lasts twice as long and reaches further).
- **Float board**: your catch rides on deck, out of the water. Sharks can't take it, and no blood trails off the float to bring them in.
- **Shark deterrent**: sharks hang back and rarely strike at you. It doesn't guard the float.
- **Twin outboards**: opens the blue-water boat drop at every site.
- **Wetsuits and fins**: camo suit, 7 mm suit (dives last longer in the cold southern water), long freediving fins.
- **Scuba**: 15-litre tank, nitrox 32 (longer no-deco time, alarms below 34 m), rebreather (no bubbles).

Saves from earlier versions keep the gear their old achievements unlocked, plus some prize money to start.

## Record prizes

Twelve prizes can't be bought, only won. Land a fish at the biggest size its species grows to, with a clean or stone shot, and keep it legally at the weigh-in. About one fish in a hundred is that big, and the fish card turns gold when you're aiming at one. The prizes are cosmetics (golden speargun, pāua wetsuit, glow fins, rainbow shaft, golden float) and mild cheats (slow motion while you aim, iron lungs, ghost mode, gorilla grip, true tip, self-loading gun, jet fins). Switch them on or off in the menu.

## Sneak meter

While you hunt, the sneak meter shows how alert the fish you're stalking is, from "Unaware" to "About to bolt". It also says what's giving you away (moving fast, swimming straight at it, staring at it, your bubbles) and how close the fish lets you come before it gets nervous. An eye over the fish fills up as it notices you.

## Put it on GitHub Pages

1. Create a new public repository on GitHub, for example `bottom-time`. (If you already have one from the last version, open it instead.)
2. On the repository page choose **Add file → Upload files**, drag in everything in this folder (`index.html`, `README.md`, `.nojekyll`) and commit. Uploading over the old `index.html` replaces it.
   - `.nojekyll` is hidden on a Mac; it's optional, so skip it if you can't see it.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute or two the game is live at `https://YOUR-USERNAME.github.io/bottom-time/`. Send that link to your play tester. After an update, a hard refresh (Ctrl+Shift+R, or Cmd+Shift+R on a Mac) makes sure the browser loads the new version.

To play without GitHub, double-click `index.html`. It needs an internet connection: it loads three.js and the fonts from public CDNs. Everything else is inside the one file.

## Controls

- **Mouse** or **arrow keys**: look. **W A S D**: swim where you look. **Shift**: kick hard.
- **C**: duck dive. **Space**: swim up. At the surface you float and breathe until you dive.
- **Z** (or hold right mouse): raise the gun. **X** (or left mouse): shoot. With a fish on, hold **X** to pull, **E** lets go to the float, **K** cuts the line.
- **F**: grab a cray or pāua, crush a kina for burley, climb out at the boat or rocks.
- **Esc**: pause. **M**: map of the coast.
- Game controller and touch screens work too.

## For play testers

Best on a desktop browser (Chrome, Edge, Firefox or Safari). Phones work, with lighter graphics. Your progress saves in the browser, across all four sites.

Useful things to report: the frame rate on your machine, anything that looks broken, anything that's confusing in the first few minutes, which site you liked most, and whether the fish feel too easy or too hard.

## Credits

- Map of New Zealand: coast, lakes and rivers from Natural Earth (public domain). Relief from the Terrain Tiles on AWS: Global ETOPO1 terrain data, U.S. National Oceanic and Atmospheric Administration; GMTED2010 and SRTM terrain data courtesy of the U.S. Geological Survey.
- Diver bodies: Quaternius, Universal Base Characters (CC0).
- Rock and sand detail: Poly Haven, Rock Face 03 and Aerial Beach 01 (CC0). Sky: Poly Haven, Kloofendal 48d Partly Cloudy (CC0).
- three.js (MIT licence). Fonts: Saira Condensed and Barlow Semi Condensed from Google Fonts (SIL Open Font License).
- Sizes and bag limits follow the Auckland East recreational rules, simplified for the southern sites; dolphin and orca behaviour follows DOC's marine mammal rules. It's a game: check the MPI and DOC rules before a real dive.
