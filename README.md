# spectral-workbook

An electron app to fetch spectral data, crunch calculations, and upload to publiclab's spectral workench. This project is in prototype stage. While other spectrometer software exist, currently there aren't any known programs designed to fetch live spectral data directly from a raspberry pi. The goal is to have a dedicated software for desktops to upload webcam and raspberry pi data directly to spectralworkbench to greatly enhance the data collection experience. Data can be previewed and downloaded/uploaded with basic calculations and calibration for a faster workflow.

## Getting Started

To try out the project or to make modifications, simply clone or download the repository.

### Prerequisites

The requirements to run this app are node.js, npm, and electron. If you install node.js, it comes with npm so you should only have to install electron after that using:

```
npm install --save electron
```

### Run the app

To run the app:
1. Open a cmd terminal
2. Navigate to the spectral-workbook directory
3. Execute:

```
npm start
```

The program should start and the app window should automatically open and load.

### Screenshots

The prototype app view:
![Image of prototype screenshot](https://raw.githubusercontent.com/cryptoclidus/spectral-workbook/master/screenshots/screenshot.JPG)
