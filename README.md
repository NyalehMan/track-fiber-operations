# TRACK Solutions · Fiber Operations

This folder contains the static UNN demonstration for GitHub Pages. `index.html` contains the application, branding, map context, and modeled demo network. No repository build or server is needed.

## Publish on GitHub Pages

1. Create or open the GitHub repository for this demo. Upload `index.html` and `.nojekyll` to the root of the branch you intend to publish, such as `main`. Upload the contents of this folder directly to that location.
2. In the repository, go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Select your branch and **/(root)**. Save.
3. After deployment, open the address shown in **Settings → Pages**. A project site normally uses `https://OWNER.github.io/REPOSITORY/`. Check that the map opens at Menglait. In **Plan fiber**, place a terminal, select a named building, and save a drop. Check **3D terrain** and **Underground**. **Offline backdrop** is available if the online map cannot load.

[GitHub Pages publishing setup](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## Demo data

The app packages mapped street and building context, an indicative published FTTH footprint, and modeled fiber assets and service IDs. Local browser drafts, tags, imports, and activity are stored at the address used to open the app. Only the static demo files belong in the published folder. Keep operator imports and exports with real service references outside the site.

Open **Alerts & SLA** to simulate an asset outage against the modeled topology, see the affected hardware and premises, and compare elapsed downtime with a configurable restoration target. The app saves outage history, location snapshots, and maintenance records in the browser. Service dependencies and health monitoring are simulated. Installation, inspection, and maintenance dates can be entered per asset in **Health & maintenance**.

The street and building-name data derived from OpenStreetMap in the embedded `region-data` and `menglait-data` blocks are available under the Open Database License. Building-height estimates and the modeled network are documented in the project source. [OpenStreetMap contributors and licence](https://www.openstreetmap.org/copyright) · [Open Database License](https://opendatacommons.org/licenses/odbl/1-0/) · [UNN published indicative coverage](https://unn.com.bn/fibre-network)

Hardware photographs are from Wikimedia Commons and bundled as resized previews. Each asset card links to the photograph, creator, and licence. [Distribution terminal](https://commons.wikimedia.org/wiki/File:CHT_6_Port_Fiber_Distribution_Box_20190504a.jpg) · [Installed access cover](https://commons.wikimedia.org/wiki/File:Pacific_Telephone_and_Telegraph_utility_hole_cover.jpg) · [Splice closure](https://commons.wikimedia.org/wiki/File:Fiber_optic_splice_closure_(31613409963).jpg) · [Distribution hub](https://commons.wikimedia.org/wiki/File:Fibre_broadband_Fibre_Distribution_Hub_outdoor_enclosure_Tottenham,_London_01.jpg) · [Cable reel](https://commons.wikimedia.org/wiki/File:Optical_fibre_cable_reel_Finland.jpg) · [Premises equipment](https://commons.wikimedia.org/wiki/File:Boitier-Fibre-Orange_-_IMG_6459.jpg)
