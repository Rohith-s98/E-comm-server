# E-comm-server

Node.js + Express backend for my [E-Commerce-Web-Site](https://github.com/Rohith-s98/E-Commerce-Web-Site) (2023). It creates Stripe payments for the React storefront.

## Run locally
```bash
npm install
cp config.env.example config.env   # then add your own Stripe test secret key
node server.js                     # http://localhost:4242
```

`config.env` is gitignored, so secrets never get committed.
