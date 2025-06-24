# step-tracker-site
Part of a custom pcb project to create a shareable web app to display the steps counted and pace. This is a simple Web Bluetooth app for reading step count and pace data from a custom fitness device using a BLE module (CMT4502).

## Features
- Connects to BLE using Web Bluetooth API
- Displays step count and pace (e.g. "walk", "run")
- Works in Google Chrome on laptops or Android phones with BLE

## Hosting
This site is hosted using **GitHub Pages**.

To deploy:
1. Push index.html to your GitHub repo
2. Go to Settings > Pages
3. Enable GitHub Pages from the `main` branch
4. Your site will be live at:
   https://24570335.github.io/step-tracker-site

## BLE Details
- Service UUID: `0000ffe0-0000-1000-8000-00805f9b34fb`
- Notify Characteristic UUID: `0000ffe4-0000-1000-8000-00805f9b34fb`
- Expected data format: `STEPS:1234,PACE:walk`

## Browser Requirements
- Google Chrome (desktop or Android)
- HTTPS required
