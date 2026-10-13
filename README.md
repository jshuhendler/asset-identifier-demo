# Asset Identifier Automation Demo

**Interactive JavaScript Application | Laboratory Workflow Automation**

A browser-based demonstration of a tool designed to simplify bulk corrections of equipment identifiers in laboratory asset management systems.

**[Try the Live Demo](https://jshuhendler.github.io/asset-identifier-demo/)**

## Overview

Manually correcting mislabeled equipment identifiers can be repetitive and time-consuming. This project demonstrates how JavaScript can automate identifier corrections across multiple selected records, reducing manual editing and improving consistency.

The application uses fictional equipment records and operates entirely within the browser.

## Features

- Select individual assets or multiple records at once
- Automatically swap serial number and asset tag values
- Update the corresponding equipment identifier
- Verify that corrected values match expectations
- Display processing progress and record status
- Reset the demonstration to its initial state

## Technologies

- **JavaScript (ES6+)** — Data processing and application logic
- **HTML5** — Application structure
- **CSS3** — Responsive, dark-themed interface
- **GitHub Pages** — Static website hosting

## How It Works

1. Select the equipment records requiring correction.
2. Click **Swap Selected**.
3. The application processes the records sequentially.
4. Identifier fields are updated and checked.
5. Each record displays its verification status.

## Technical Notes

The application separates demonstration data from processing logic and updates the interface dynamically using browser DOM APIs.

Processing delays simulate asynchronous operations for visualization purposes. All updates take place in browser memory; the demo does not communicate with a backend or persist changes.

## Background

This demonstration was inspired by a real-world laboratory workflow automation project. It is an independent portfolio example using synthetic records, without connecting to production systems.

## Author

**Jonathan Shuhendler**

Python development | Data analysis | Laboratory automation

## Disclaimer

This is an educational demonstration. All records are fictional, and no production asset management system is accessed.
