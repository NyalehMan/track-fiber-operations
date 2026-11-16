# TRACK Solutions · Fiber Operations

This folder contains the static Fiber Operations site for GitHub Pages. `index.html` includes the application, branding, map context, and modeled network. No repository build or server is needed.

## Publish on GitHub Pages

1. Open the GitHub repository for the site. Upload `index.html` and `.nojekyll` to the root of the branch you intend to publish, such as `main`.
2. In the repository, go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Select your branch and **/(root)**. Save.
3. After deployment, open the address shown in **Settings → Pages**. A project site normally uses `https://OWNER.github.io/REPOSITORY/`. Check that the map opens at Menglait. In **Plan fiber**, place a terminal, select a named building, and save a drop. Check **3D terrain** and **Underground**. **Offline backdrop** is available if the online map cannot load.

[GitHub Pages publishing setup](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## Network data

The app packages mapped street and building context, an indicative published FTTH footprint, and modeled fiber assets and service IDs. Local browser drafts, tags, imports, and activity are stored at the address used to open the app. Existing map connection and import tools are under **Layers → Map connections**. Keep real service references outside the published repository.

Open **Service Assurance** to simulate an asset outage against the modeled topology and compare elapsed downtime with a configurable restoration target. Select a marker on the **Location snapshot** or an item under **Service impact** to highlight its service dependencies. The bundled networks include illustrative maintenance histories. Edits in **Health & maintenance**, outage history, and location snapshots are saved in the browser.

Open **Network map → 4G coverage** to see UNN’s predicted 4G footprint in Mukim Telisai, published 24 August 2026 at a −114 dBm downlink threshold. The estimate weights the 2021 census counts for each kampong by the share of WorldPop’s 2020 population grid inside the footprint, then sums the estimates. Nearby communications structures are mapped reference points. Operator, radio technology, and coverage per site are unverified. [UNN mobile coverage](https://unn.com.bn/mobile-network) · [UNN coverage GeoJSON](https://unn.com.bn/storage/mobile_map.geojson) · [Brunei 2021 census, Table B5](https://deps.mofe.gov.bn/DEPD%20Documents%20Library/DOS/POP/2021/ANNEX%20B.pdf) · [WorldPop population grid](https://hub.worldpop.org/geodata/summary?id=49757)

**Communications sites** also includes a historical government record naming the DST tower site at RPN Bukit Beruang. The record identifies the locality. Current equipment and the site’s serving area are unverified. [Pelita Brunei, 19 April 2014](https://www.pelitabrunei.gov.bn/Arkib%20Dokumen/2014/April/pelitabrunei_1904114.pdf)

The street, building, and mapped communications site data derived from OpenStreetMap in the embedded `region-data`, `menglait-data`, and `mobile-data` blocks are available under the Open Database License. Building-height estimates and the modeled network are documented in the project source. [OpenStreetMap contributors and licence](https://www.openstreetmap.org/copyright) · [Open Database License](https://opendatacommons.org/licenses/odbl/1-0/) · [UNN published indicative FTTH coverage](https://unn.com.bn/fibre-network)

Hardware photographs are from Wikimedia Commons and bundled as resized previews. Each asset card links to the photograph, creator, and licence. [Distribution terminal](https://commons.wikimedia.org/wiki/File:CHT_6_Port_Fiber_Distribution_Box_20190504a.jpg) · [Installed access cover](https://commons.wikimedia.org/wiki/File:Pacific_Telephone_and_Telegraph_utility_hole_cover.jpg) · [Splice closure](https://commons.wikimedia.org/wiki/File:Fiber_optic_splice_closure_(31613409963).jpg) · [Distribution hub](https://commons.wikimedia.org/wiki/File:Fibre_broadband_Fibre_Distribution_Hub_outdoor_enclosure_Tottenham,_London_01.jpg) · [Cable reel](https://commons.wikimedia.org/wiki/File:Optical_fibre_cable_reel_Finland.jpg) · [Premises equipment](https://commons.wikimedia.org/wiki/File:Boitier-Fibre-Orange_-_IMG_6459.jpg)
