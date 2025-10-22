# CarMax Stock Shares Outstanding Viewer

This web application fetches and displays the maximum and minimum common stock shares outstanding for CarMax (CIK 0001170010) from SEC EDGAR data. It allows users to query the same data for any other company by providing a different CIK number as a URL parameter.

## Features

- Retrieves and displays the maximum and minimum common stock shares outstanding since 2020.
- Supports dynamic data fetching for any company by CIK number via URL query parameter.
- Presents data in a clean and visually appealing format.

## Usage

1. Open `index.html` in a web browser.
2. By default, it fetches and displays data for CarMax.
3. To view data for another company, append `?CIK=XXXXXXXXXX` to the URL, replacing `XXXXXXXXXX` with the desired CIK number.

## Technologies

- HTML5 and CSS3 for structure and styling.
- JavaScript for dynamic data fetching and DOM manipulation.
- Fetch API for retrieving data from the SEC EDGAR database.

## Note

The application requires a network connection to access SEC data and may fail if the SEC server is unreachable or if the provided CIK is invalid.