# README

## Overview

This project is a simple HTML page that prompts users to enter a password to view a specific website. The page checks the password entered by the user and either grants or denies access based on the correctness of the password.

## Structure

The project contains the following key components:

- HTML: Defines the structure of the web page.
- CSS: Styles the web page.
- JavaScript: Contains the logic to check the password entered by the user.


## Files

- `index.html`: The main HTML file that includes the structure, styling, and password-checking script.


## HTML Structure

The HTML file is structured as follows:

1. DOCTYPE Declaration: Specifies the HTML version.
2. `<html>` tag: The root element of the HTML document.
3. `<head>` tag: Contains meta information about the HTML document, including character set, viewport settings, title, and styles.
4. `<style>` tag: Contains CSS rules to style the web page.
5. `<body>` tag: Contains the main content of the web page, including the password input field and the link to proceed.
6. `<script>` tag: Contains JavaScript code to handle password verification.

## CSS

The CSS styles are defined within a `<style>` tag inside the `<head>` section:

- `body`: Centers the text and sets the background color to `antiquewhite`.

## JavaScript

The JavaScript code is included in a `<script>` tag at the end of the HTML document. It contains a function `checkPassword` that performs the following steps:

1. Retrieves the value entered in the password input field.
2. Checks if the entered password matches the predefined password (`Chimomo23@`).
3. If the password is correct, it allows the user to proceed to the specified URL.
4. If the password is incorrect, it displays an alert message and denies access.

## Usage

1. Open the `index.html` file in a web browser.
2. Enter the password in the input field.
3. Click the link to submit the password.
4. If the password is correct, you will be redirected to the specified URL (`https://www.monkdiamonddiscovery.com`).
5. If the password is incorrect, an alert message will be displayed indicating access is denied.

## Notes

- The correct password is hardcoded as `Chimomo23@`.
- The link will only redirect if the correct password is entered.
- If the password is incorrect, an alert message will inform the user.

## License

This project is licensed under the MIT License.