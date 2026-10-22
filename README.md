# Prime Picks

Prime Picks is a mobile-friendly clothing and accessories storefront. Shoppers browse products, open a product page, add items to the cart, and place an order.

## Pages

- **Home** (`index.html`) — header, image slider, clothing grid, accessories grid, and footer.
- **Product details** (`contentDetails.html`) — preview images, description, price, and Add to Cart.
- **Cart** (`cart.html`) — selected items, item count, total, and Place Order.
- **Order placed** (`orderPlaced.html`) — confirmation after checkout.
- **Contact** (`contact.html`) — store address, email, and phone.

The home page includes the header, image slider, product grids, and footer in one file, so it can be opened directly in a browser.

## Contact

- **Address:** 42 Market Street, Suite 210, New York, NY 10013, United States
- **Email:** hello@primepicks.store and support@primepicks.store
- **Phone:** +1 (212) 555-0198 and +1 (212) 555-0142

The same address, primary email, and primary phone also appear in the footer on every page.

## Run locally

Open `index.html` in a browser. Product data is loaded from MockAPI, so the page needs an internet connection.

## How shopping works

1. The home page loads products from the MockAPI catalog and splits them into clothing and accessories.
2. A product link opens `contentDetails.html` with that product id.
3. Add to Cart stores the product id and count in a cookie and updates the cart badge.
4. The cart reads that cookie, lists the items, and shows the total in rupees.
5. Place Order opens the order confirmation page.

## Stack

- HTML, CSS, and JavaScript
- [Slick](https://kenwheeler.github.io/slick/) carousel (jQuery) for the home slider
- [MockAPI](https://5d76bf96515d1a0014085cf9.mockapi.io/product) for the product catalog and order endpoint
