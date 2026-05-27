# Lab8-Starter

## Lab Partner(s)
- Bowen Wu

## Deployed URL
https://Endless1010.github.io/Lab8_Starter/

## Graceful Degradation & Service Workers
Graceful degradation is the practice of building an application with full functionality first and then ensuring it still provides a usable experience when conditions are less than ideal — for example, on a slow network, an outdated browser, or no internet connection at all. Service workers fit naturally into this idea: by intercepting network requests and serving cached responses, they let the app continue to work when the network is unavailable or unreliable, rather than failing outright. The site is built assuming a fast, online connection, but when the network drops out the service worker steps in with cached assets and recipe data so the user still sees a functional page. In that sense, service workers are one of the main tools that make graceful degradation possible for modern web apps.

## PWA Screenshot
See `pwa.png` in the repo root.
