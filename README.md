# Papertrail Online Bookstore

A responsive, multi-page bookstore demo built with plain HTML, CSS, and JavaScript. No build step or dependencies are required.

## Run in VS Code

1. Open this folder in VS Code.
2. Install the **Live Server** extension if it is not already installed.
3. Right-click [index.html](index.html) and choose **Open with Live Server**.

You can also serve the folder with any static web server. Open `index.html` directly for basic browsing, but a local server is recommended.

## Pages and features

- Home, Books, About, Contact, Login, Register, and Cart pages share the same responsive navigation and styling.
- Search the catalog by book title, author, or category.
- Add books to the cart, adjust quantities, remove items, and see the subtotal and total update.
- Cart contents and demo account data are saved in `localStorage` on the current browser.
- Forms use native browser validation and provide inline feedback.

## Demo limitations

This is a front-end-only project. Login and registration are demonstrations, and account passwords are stored in browser `localStorage` without secure authentication. **Do not use real credentials.** Contact form submissions are not sent or saved, and checkout does not process payments. A real store needs a secure backend for accounts, messages, inventory, and payments.

Book and decorative photography is loaded from Unsplash and therefore requires an internet connection.