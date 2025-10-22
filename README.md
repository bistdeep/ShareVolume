# CarMax Shares Outstanding

## Overview
This project fetches and displays the common stock shares outstanding for CarMax (KMX) from the SEC API.

## Features
- Displays maximum and minimum shares outstanding since 2021.
- Supports dynamic fetching of data for different CIKs via URL parameters.

## Setup Instructions
1. Clone the repository.
2. Open `index.html` in a web browser.

## Usage
- To view CarMax data, simply open `index.html`.
- To view data for another company, append `?CIK=XXXXXXXXXX` to the URL, replacing `XXXXXXXXXX` with the desired CIK.

## Code Explanation
- The HTML structure includes a title, headings, and sections for displaying data.
- JavaScript fetches data from the SEC API and updates the DOM based on the fetched data.

## License
This project is licensed under the MIT License.