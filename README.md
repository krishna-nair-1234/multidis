# STP Control Dashboard

A simple frontend dashboard for sewage treatment plant monitoring.

## What it does

- Displays inlet and outlet readings for:
  - COD
  - BOD
  - TSS
  - TDS
  - pH
  - Nitrite + Nitrate as N
  - Fecal coliform
- Shows a dashboard summary with counts of healthy, warning, and critical parameters.
- Applies basic operational rules:
  - TSS increase: recommend pumping treated water back in to dilute solids.
  - BOD/COD increase: recommend stopping the plant briefly to increase residence time.

## Run

Open `index.html` in a browser.

## Notes

- The current version uses manual entry plus browser local storage.
- If you want live Google Sheets sync, the sheet needs to be published or exposed through an API/export URL.
