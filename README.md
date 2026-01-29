# strongdog_prox

This project now supports a fallback mechanism for games and images. By default, it uses `strongdog.com` as the base URL. For games tagged with `source: 'dv-service-lfs'` in `cards-data.js`, it will use `dv-service-lfs.4simpleproblems.workers.dev` as the base URL.

## How to use

To avoid CORS issues, it's recommended to serve these files from a web server. You can use a service like `raw.githack.com` by providing the URL to the `index.html` file in this repository, or by enabling GitHub Pages for this repository.