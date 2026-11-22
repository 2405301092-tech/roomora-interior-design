# ROOMORA — Design Your Dream Space

A responsive, static interior-design website created for the **Build and Deploy a Website** assessment.

## Pages
Home, Explore Rooms, Design Studio, Inspiration Gallery, About, Contact.

## Features
- Responsive desktop and mobile navigation
- Working page navigation via URL hashes
- Gallery category filters
- Design Studio room/style/palette/budget selection
- Save design preferences to local browser storage
- Contact form validation (demo only; does not send messages)

## Run locally
Open `index.html` in a browser. For a local web server, run `python -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Deploy using GitHub + Cloudflare Pages
1. Create a GitHub repository and upload `index.html` and `README.md` to the repository root.
2. In Cloudflare, choose Workers & Pages → Create → Pages → Connect to Git.
3. Select the GitHub repository.
4. Choose **no framework** / static HTML; leave the build command blank and use `/` as output directory if prompted.
5. Deploy and verify the assigned `*.pages.dev` URL in a private browser window.

## Important limitations
This is an independent implementation based on the ROOMORA UI concept and previously shared design screenshots, **not** an exact export of the Google Stitch prototype. Photographs load from Unsplash and require an internet connection. The contact form is demonstration-only; no backend is provided. Design selections save only in the current browser.

## Assessment identity
Student: Sneha
Roll number: 2405301092
Original UI prototype: https://stitch.google.com/preview/3127328184915743218?node-id=dbc6123dd3a34de6b5ebcfe6a2fec965
