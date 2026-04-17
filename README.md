# Free Barcode Generator & QR Code Generator

Free barcode generator and QR code generator built as a simple static webpage. This project is designed for fast single-code creation, PNG download, and direct deployment on GitHub Pages.

It is positioned as a lightweight companion page related to [Barcode Designer](https://barcodes.design/), with SEO copy and on-page linking aligned around keywords such as `barcode generator`, `qr code generator`, `barcode design`, `qr code design`, `bardecode design`, and `free`.

## What This Project Does

- Generate a single QR code directly in the browser
- Generate a single barcode in common formats such as `CODE128`, `EAN13`, `UPC`, and `ITF14`
- Save the current barcode or QR code as a PNG image
- Run as a pure static site with no backend and no build step
- Work well as a free landing page or free tool page connected to `https://barcodes.design/`

## SEO Positioning

This page is intended to support search visibility around topics like:

- free barcode generator
- free qr code generator
- barcode generator
- qr code generator
- barcode design
- qr code design
- bardecode design
- single barcode generator
- Barcode Designer

The page content, metadata, Open Graph tags, Twitter tags, structured data, and on-page related links have been tuned to stay relevant to the `barcodes.design` ecosystem while still remaining an independent static tool page.

## Relationship To Barcode Designer

- Official site: [https://barcodes.design/](https://barcodes.design/)
- This project uses `https://barcodes.design/` as the default QR code content
- The UI includes direct related links back to Barcode Designer
- SEO metadata references Barcode Designer as the related workflow and parent product context

This makes the page useful as a free single-code generator while still helping users discover the broader Barcode Designer workflow for reusable templates, print-ready labels, and advanced barcode design use cases.

## Deploy To GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html`, `README.md`, and the `assets/` folder.
3. In GitHub repository settings, open `Pages`.
4. Set the source to your main branch root.
5. Save and open the generated site URL.

## Local Dependencies

- Local vendor files are stored in `assets/vendor/`
- The page loads local vendor files first for more reliable hosting
- Public CDN sources are only used as fallback
- Barcode formats like `EAN13`, `UPC`, and `ITF14` require valid numeric input rules

## Notes

- This is a static HTML project, so it is easy to host, fork, and customize
- The page language is English
- The current default content generates a QR code for `https://barcodes.design/`
