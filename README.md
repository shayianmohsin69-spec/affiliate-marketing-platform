# Affiliate Marketing Platform

I created this product guide to display useful finds with images, descriptions, display prices and links to external retailers. The Express backend tracks outbound clicks, supports product management and provides an admin report. A disclosure section explains how affiliate links may work.

## Requirements
- Node.js 18 or newer
- npm

## Run locally
```bash
npm install
npm start
```
Open http://localhost:3001.

## Admin setup
The demo key defaults to `change-this-admin-key`. Set a private `ADMIN_KEY` environment variable before hosting. Enter the key in the Admin section to add products or see click totals.

## Affiliate links
The starter catalogue uses general Amazon and Alibaba pages, not commission-bearing affiliate links. Replace each destination with a tracking URL from an affiliate program you have been approved to use. Click tracking records outbound visits only; it cannot confirm purchases or commission.

## Deployment notes
This demo saves data in a local JSON file. Use persistent storage and stronger authentication before production deployment. Product photos are loaded from remote image URLs.