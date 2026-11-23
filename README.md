# vikramja.github.io

Hosts the **public** key that Tesla's Fleet API requires for the Home
Assistant `tesla_fleet` integration, at
`/.well-known/appspecific/com.tesla.3p.public-key.pem`.

- Only the public key is here. The matching private key stays on the Home
  Assistant server (`/config/tesla_fleet.key`) and is never committed anywhere.
- `.nojekyll` makes GitHub Pages serve the `.well-known/` directory.
- If the key is ever rotated, replace the file here, and add the virtual key
  to the car again in the Tesla app (`https://www.tesla.com/_ak/vikramja.github.io`).

Setup notes: issue vikramja/Default#38.
