# Amazon Design Price Calculator

A responsive, standalone static web app. No database, API keys, or environment variables are required.

## Run locally
Open `index.html` in a browser.

## Deploy to Vercel
1. Create a new GitHub repository and upload `index.html` (and this README).
2. Sign in to https://vercel.com and choose **Add New → Project**.
3. Import the GitHub repository.
4. Select **Other** as the framework preset if Vercel asks.
5. Leave Build Command and Output Directory empty/default. The site is a static HTML app.
6. Click **Deploy**. Vercel will provide a public `*.vercel.app` URL.

You can also deploy by dragging the project folder into Vercel's dashboard if the current dashboard flow offers manual deployment, or use the Vercel CLI from this folder.

## Pricing logic
- Listing Images: first product $30, each additional product +$20.
- Images 1 to 5 included; each image above 5 adds $3 per product.
- First variation included; each additional variation adds $8 per product.
- Outline content supplied by the client: 20% off Listing Images.
- Basic A+: $25 per product.
- Premium A+: $35 per product.
- Additional A+ variations beyond the first: $8 each per product.
- Storefront: $80 base, including up to 4 pages and 6 modules per page.
- Each page after 4: $20.
- Each module above 6 on a page: $3.
- 2 selected services: 8% bundle discount.
- 3 selected services: 20% bundle discount.

## Change currency conversion
Edit `USD_TO_PKR = 280` in the script near the bottom of `index.html`. The conversion is illustrative, not a live exchange rate.
