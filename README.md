# Lab8-Starter

## Lab Partner(s)
Solaiman Alwazir

## Deployed GitHub Pages URL
https://salwazir.github.io/Lab8_Starter/

## Graceful Degradation & Service Workers
Graceful degradation is the practice of building an application with full functionality first and then ensuring it still works (with reduced capability) when ideal conditions aren't met. Service workers are a perfect example of this idea in action: a web app is normally designed assuming the user has an internet connection, but service workers let the app continue functioning when that connection drops. By intercepting network requests and serving cached responses, a service worker allows the app to degrade gracefully — losing some freshness or interactivity when offline, but still loading the HTML, CSS, JS, images, and recipe data so the user can keep using it. The app starts at "max technology" (live network) and falls back to a cached version when needed, which is graceful degradation in practice.

## PWA Screenshot
See `pwa.png`.
