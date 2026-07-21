# C172 Flugplanung v2026 - VFR flight planning tool 2026

> **C172 Flugplanung is a browser-based VFR planning suite for the Cessna 172, combining navlog, weight and balance, fuel, and performance planning in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/colebenneio7227/c172-flugplanung-v2026?style=flat-square)](https://github.com/colebenneio7227/c172-flugplanung-v2026)

---

<p align="center">
  <a href="https://colebenneio7227.github.io/c172-flugplanung-v2026/">
    <img src="https://img.shields.io/badge/Download-C172%20Flugplanung%20Latest-brightgreen?style=for-the-badge" alt="Download C172 Flugplanung">
  </a>
</p>

> **[Download Latest Build - C172 Flugplanung v2026](https://colebenneio7227.github.io/c172-flugplanung-v2026/)**

---

[Download Latest Build](https://colebenneio7227.github.io/c172-flugplanung-v2026/)

---

## Overview

C172 Flugplanung targets VFR trip prep for the Cessna 172 and brings the main planning steps into one web application. It helps keep route planning, loading, fuel, and aircraft performance in the same place, so the workflow stays organized from start to finish.

It is intended for pilots who want a browser-first planning environment with authenticated access and cloud synchronization. With Firebase Auth in the workflow, the same planning session can stay available across devices instead of being limited to a single machine.

---

## What it includes

- Navlog planning for route preparation and flight planning
- Weight and balance calculations for Cessna 172 operations
- Fuel planning support for trip planning and endurance checks
- Performance planning to help estimate aircraft operating needs
- Cross-device cloud synchronization for accessing plans from more than one device
- Login required for authenticated use
- Web-based interface for browser access without a local app install
- Built around VFR flight planning workflows

---

## Installation

Clone the repository or download the project files, then open the web app in a browser.

git clone https://github.com/colebenneio7227/c172-flugplanung-v2026.git
cd c172-flugplanung

If the project is being hosted locally, start the app with your usual static web server or development workflow for HTML-based projects.

---

## How to use it

1. Sign in through the application login flow.
2. Start a new VFR planning session for the Cessna 172.
3. Enter route details to build the navlog.
4. Add loading, fuel, and performance data as needed.
5. Review the planning results and continue editing from another device if cloud sync is enabled.

For recurring planning, keep the same account so synced data stays available across supported devices.

---

## Configuration

Settings and saved planning data are tied to the web application and its authenticated cloud workflow.

Typical environment-dependent items may include:
- Firebase Auth setup
- Cloud synchronization settings
- Saved planning records and user session data

If the project includes local configuration files in your deployment, store them with the rest of the web app assets and update them according to your environment.

---

## Requirements

- Web browser
- Internet access for login and cloud sync features
- Firebase Auth support for authenticated access
- A hosting setup for the web application
- Storage for saved planning data if deployed with persistent sync features

---

## FAQ

### Do I need an account?
Yes. The application uses login-based access.

### Can I use it on multiple devices?
Yes, cloud synchronization is included for cross-device use.

### What planning tasks does it cover?
It supports navlog planning, weight and balance, fuel planning, and performance planning.

### Where do I update the app?
Use the latest build link above to access the current version.

### What if sync or login does not work?
Check the browser session, network access, and Firebase Auth configuration used by the deployment.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
