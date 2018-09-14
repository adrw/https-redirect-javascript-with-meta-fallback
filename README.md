HTTPS Redirect with Javascript and Meta Fallback
===

Redirecting HTTPS links is not possible with DNS 301 URL redirect records.

For example, using DNS alone `https://domain1.com/xyz.html` can not be redirected to `https://domain2.com/xyz.html`.

Instead, the HTTPS for `domain1.com` must terminate at a server before the client can be redirected to `domain2.com`.

Thus this repo: 
---
- A [guide](#guide) for how to use Github Pages as that terminating server
- Simple, styled, HTML [templates](./src) that you can use for your own redirection repo
- An [example repo](https://github.com/adrw/andrewparadi.com) using this framework for HTTPS redirects
- A [live demo](https://www.andrewparadi.com/#noredirect) of the redirect page

![Styled HTTPS Redirect for andrewparadi.com](/redirect.png)

Guide
---
1. Coming soon...

Resources
---
- [Repo on Github](https://github.com/adrw/https-redirect-javascript-with-meta-fallback)
- [adrw/andrewparadi.com](https://github.com/adrw/andrewparadi.com) Redirects using this framework for `https://www.andrewparadi.com` -> `https://andrew.fm`
- [adrw/high-resolution-compressed-images](https://github.com/adrw/high-resolution-compressed-images) 4k <50kb images used as backgrounds on websites
- [Trianglify](https://github.com/qrohlf/trianglify) by [@qrholf](http://qrohlf.com/) background art before [ImageAlpha](https://pngmini.com/) PNG compression
