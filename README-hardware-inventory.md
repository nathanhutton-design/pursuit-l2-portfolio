# Hardware Inventory

**Live demo:** https://nathanhutton-design.github.io/Hardware-Inventory/

## Problem

Tracking IT hardware assets in a spreadsheet gets messy fast — no validation, no easy export, and no consistent record of status (active, in storage, in repair, decommissioned) or warranty dates as equipment moves around an org.

## Solution

A lightweight, browser-based hardware asset tracker preloaded with spreadsheet data. It gives IT staff a structured form for adding and editing asset records, keeps edits locally in the browser, and exports the full inventory to CSV on demand.

## Key Features

- Structured asset record form: Asset ID, Device Type, Manufacturer, Model, Serial Number, Hostname, Assigned To, Department, Location, Purchase Date, Warranty Expiry, Status, OS, and Notes
- Status tracking (Active / In Storage / Repair / Decommissioned)
- Preloaded with existing spreadsheet inventory data
- Edits persisted to browser localStorage
- One-click CSV export

## Tech Stack

- Frontend: HTML/CSS/JavaScript (client-side only, no backend)
- Storage: browser `localStorage`
- Export: CSV

## Screenshot

<!-- Add a screenshot of the inventory table here, e.g.: -->
<!-- ![Hardware Inventory screenshot](./screenshot.png) -->

## Notes

Built independently, before the Pursuit Fellowship, as a personal IT asset tracker.
