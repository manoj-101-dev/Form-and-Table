# JavaScript Form Data to Table

This code snippet demonstrates capturing form data and appending it to an HTML table dynamically.

## Description

The provided JavaScript code listens for the form submission event and captures input data from various form fields. It then dynamically generates a new table row (`<tr>`) containing the captured data and appends it to an existing HTML table (`#myTable tbody`).

## Code Functionality

- Upon form submission, the code prevents the default form submission behavior (`e.preventDefault()`).
- It collects data from the form inputs (first name, last name, address, pincode, gender, food, state, country).
- Creates a new table row (`<tr>`) with table data cells (`<td>`) containing the captured form values.
- Appends the new row to the specified table body.

## Usage

1. Ensure the HTML file contains a form (`<form>`) with input fields for various data (e.g., first name, last name, address, etc.).
2. Add an HTML table (`<table>`) with an empty `<tbody>` having an ID (`myTable`) where the form data will be appended.
3. Set appropriate IDs for form elements (`first-name`, `last-name`, etc.) to capture user input.

## How it Works

- The JavaScript code uses `addEventListener` to listen for the form submission event.
- It retrieves values from form elements using their IDs (`getElementById` and `querySelector` methods).
- Creates a new table row (`<tr>`) dynamically, populating it with captured form data.
- Appends the new row to the specified table body.

-[Live-Site](https://manoj-101-dev.github.io/Task15/)
