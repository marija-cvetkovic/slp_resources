# Speech Therapy Articulation Games

Interactive, clinician-supervised articulation practice web apps designed for Speech-Language Pathologists (SLPs) (and SLPAs!) on **iPad (Safari)** and **desktop computers**. Students earn 5 correct productions to unlock a mystery silhouette challenge!

## Current Live Games

Each game is accessible at its own live link:

* **Guess That Pokémon!** → `https://marija-cvetkovic.github.io/slp_resources/` (`index.html`)

* **Guess That Minecraft Mob!** → `https://marija-cvetkovic.github.io/slp_resources/minecraft.html`

## Clinical & App Features

* **Target Sounds & Word Positions:** Covers 24 English phonemes plus consonant blends, strictly filtered by **Initial**, **Medial**, **Final**, or **Mixed** word positions, at either **Word** or **Sentence** level.

* **Client Profiles (`localStorage`):** Create, switch, and manage individual client profiles directly in the browser. Each client's target goals, custom word lists, reward progress, and session data are saved separately.

* **Cueing Level Tracking:** Toggle **Modeled: ON / OFF** before scoring to track **Spontaneous/Independent** vs. **Modeled** productions separately.

* **Custom Word Lists (`.txt` & `.csv`):** Import custom practice targets per client.

  * **TXT format:** One word or sentence per line.

  * **CSV format:** Requires a `word` column; optional `sound`, `position`, and `level` columns.

* **Session Data Export:** View live accuracy breakdowns and export trial logs to `.csv` (for the active client or all clients at once) or copy directly to your clipboard.

* **iPad & Touch Optimized:** Built with zero-delay touch handling, large tap targets, and iOS Share Sheet support.

## How to Install on iPad (Home Screen App)

Opening `.html` files directly from Mail or Messages on iPad uses Apple's Quick Look viewer, which blocks interactive buttons. Instead, install each live GitHub Pages link to your Home Screen:

1. Open **Safari** on your iPad and navigate to either the Pokémon or Minecraft URL above.

2. Tap the **Share** button (square with an upward arrow) in the Safari toolbar.

3. Scroll down and tap **Add to Home Screen**.

4. Name the shortcut (e.g., *Speech Pokémon* or *Speech Mobs*) and tap **Add**.

Repeat for the second link to have both games saved as separate full-screen apps on your iPad.

## Clinical Disclaimer

These tools are designed for **SLP-supervised articulation practice**. The supervising clinician determines production accuracy and appropriate cueing levels. All client data is stored locally in the device's browser (`localStorage`) and is not transmitted to any external server.
