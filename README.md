# The Great Fire of London — Pepys, Wren & the Rebuilding

This is a standalone educational mini-website.

## What is included

- Interactive Leaflet/OpenStreetMap map
- Approximate fire-damage polygon
- Reconstructed teaching route for Samuel Pepys
- Links to Google Maps for key locations
- Historical Hollar fire map
- Modern photographs of Wren churches
- Architectural analysis of Wren's parish churches
- Dedicated St Paul's Cathedral section
- Architecture/safety discussion including windows, sills, parapets and materials
- Interactive reveal boxes and quiz
- Source and image-credit information

## Run it locally

Double-click `index.html`, or right-click it and open it in a browser.

Because the website loads maps, Leaflet and some images from the internet, an internet connection is required for the full experience.

## Upload to GitHub Pages

1. Create a new GitHub repository, for example `great-fire-london`.
2. Upload `index.html` and this README.
3. In GitHub go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/root`.
6. Save.
7. GitHub will provide a public website address.

No build process, Node.js or npm is required.

## Important licensing note

The website deliberately links to Wikimedia Commons images rather than pretending they are all public-domain. Each image has an attribution/source link in the page. Check the individual licence before changing the site or using it commercially.

The historical Hollar map used here is recorded by Wikimedia Commons as public domain by age. Modern photographs have their own Creative Commons licences and attribution is provided.

The map uses OpenStreetMap tiles and attribution is included.

Google Maps is used only through normal search links; no Google Maps API key is required.

## Historical accuracy note

The Pepys route is a teaching reconstruction. It uses the places described in Pepys's diary and modern coordinates. It is **not** presented as a precise GPS reconstruction.

The fire-damage polygon is also deliberately labelled approximate. For a more detailed historical GIS layer, the next version could use a georeferenced historical map or published GIS data.

## Suggested next upgrade

Add a second map mode that switches between:
1. modern OpenStreetMap;
2. Hollar's historical fire map;
3. Wren's proposed rebuilding plan.

This would make the comparison between 1666, Wren's proposal and today's City particularly powerful.


## Three-layer historical map

The main Pepys map now has three student-selectable views:

1. **1666 fire damage** — Hollar's post-fire map, showing the ruined area.
2. **Wren's proposed rebuilding plan** — the London Museum image of Wren's proposed redesign.
3. **Present-day London** — the OpenStreetMap base with Pepys's route and church markers.

The historical maps are implemented as Leaflet image overlays positioned approximately over modern London coordinates. They are deliberately described as teaching overlays rather than precision GIS/georeferenced datasets.

The Wren image is supplied by London Museum under **CC BY-NC 4.0**. The Hollar fire map uses the public-domain Wikimedia Commons reproduction. See the links and credits in `index.html`.
