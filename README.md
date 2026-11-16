# Redstone Holdings ordering app (starter version)

## Included
- Mobile-friendly product catalogue for CG150 aftermarket parts
- Search and category filtering
- Shopping cart and quantities
- Checkout details for collection or nationwide courier delivery
- WhatsApp order message
- EFT selection (bank details are deliberately not embedded)

## Before publishing
1. Replace the sample catalogue in `index.html` with your actual products and prices. Search for `const products =`.
2. Confirm the WhatsApp order numbers in the `contactChoice` dropdown are correct.
3. Replace the red `R` mark with your supplied Redstone logo when you provide the logo image.
4. Confirm your collection address, courier process, returns policy and business contact details.
5. Test orders on your own phone before sharing the link.

## Publish free with GitHub Pages
1. Sign in to https://github.com and create a new public repository named `redstone-ordering-app`.
2. Upload `index.html`, `manifest.webmanifest` and `sw.js` from this folder to the repository root.
3. Open repository Settings -> Pages.
4. Under Build and deployment, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish. Your website address will be shown in Settings -> Pages.
6. Open the address in Chrome on Android. Use the browser menu -> Install app or Add to Home screen.

## Important
- This is a working starter catalogue, not a fully configured live store: the listed products are starter examples and all prices are blank until you enter confirmed prices.
- WhatsApp checkout opens a prefilled order message. The customer must press Send in WhatsApp.
- EFT payment is handled manually: send banking details directly after confirming the order. Never place sensitive banking credentials in public website code.
- GitHub Pages is static hosting. It does not provide secure customer accounts, central stock synchronisation, automatic payment verification or an order-management dashboard.
