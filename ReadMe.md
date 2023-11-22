# Advanced PayPal Integration

This repository contains code for an advanced PayPal integration on a blank page in a WordPress site.

## Table of Contents

- [Overview](#overview)
- [File Structure](#file-structure)
- [Instructions](#instructions)
- [Notes](#notes)

## Overview

The integration utilizes PayPal JavaScript SDK to create and capture orders for online payments. The code is implemented on a blank HTML page within a WordPress site.

## File Structure

- `index.html`: HTML structure for the PayPal integration page.
- `script.js`: JavaScript code handling the PayPal SDK integration.
- `styles.css`: Custom CSS styles for the integration page.

## Instructions

Follow these steps to integrate and test the PayPal functionality on your WordPress site:

1. **Clone the Repository:**
   ```bash
   git clone [repository_url]
   cd [repository_folder]/paypal-integration
   ```

HTML Page:

Copy the content of index.html into a new WordPress page.
Customize the page title as needed.
JavaScript (script.js):

Replace 'YOUR_CLIENT_ID' with your actual PayPal Sandbox or Live Client ID.
CSS Styles (styles.css):

Customize the styles if needed.
Upload Files:

Upload the paypal-integration folder to your WordPress theme directory.
Link Stylesheet and Scripts in WordPress Theme (header.php):

Edit the header.php file in your theme.
Add the following lines within the <head> section:

Replace [theme_directory] with the actual path to your theme directory and 'YOUR_CLIENT_ID' with your PayPal credentials.
View the Page:

Save your changes and visit the WordPress page with the integrated PayPal functionality.
