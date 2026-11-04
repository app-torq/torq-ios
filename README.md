<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/app-torq/torq/main/docs/assets/torq-logo-w-title-dark.svg">
  <img alt="torq" src="https://raw.githubusercontent.com/app-torq/torq/main/docs/assets/torq-logo-w-title-light.svg" width="280">
</picture>

**torq for iOS: a native app for the self-hosted maintenance logbook.**

[![Status](https://img.shields.io/badge/status-on%20ice-9cf?logo=snowflake&logoColor=white)](#why-on-ice)
[![Use instead](https://img.shields.io/badge/use%20instead-torq%20web%20app-2496ED?logo=safari&logoColor=white)](https://github.com/app-torq/torq)
[![Platform](https://img.shields.io/badge/platform-iOS-black?logo=apple&logoColor=white)](#)
[![License: MIT](https://img.shields.io/github/license/app-torq/torq-ios)](LICENSE)

[torq server](https://github.com/app-torq/torq) · [Demo](https://demo.torq-app.tech) · [Use torq on your phone](#use-torq-on-your-phone-today)

</div>

> [!IMPORTANT]
> **This project is on ice.** There is no app to install, and none is in development right now. Use the [torq web app](https://github.com/app-torq/torq) on your phone instead, see below.

## Why on ice

torq would never be in the App Store, but even installing an iOS app outside of it, through [AltStore PAL](https://altstore.io) in the EU or as an ad-hoc build, requires a paid **Apple Developer Program membership of 99 USD per year**. The only free way, self-signing with your own Apple ID, expires every 7 days, and that's not something to ask of users.

For a free, self-hosted hobby project, that fee isn't feasible right now. torq's web app is getting better on phones instead, as a progressive web app (PWA) you can put on your home screen. It covers the same ground without an install.

If enough people want a native app and would chip in to cover the developer fee, it can be picked up again. The groundwork is in place: the torq server already supports token sign-in for apps and publishes its API contract with every release. Let us know with a feature request in the [torq repository](https://github.com/app-torq/torq/issues).

## Use torq on your phone today

torq's web interface is built for phones, too. Put it on your home screen and it opens like an app:

- **iPhone / iPad (Safari):** open your torq address, tap **Share** → **Add to Home Screen**.
- **Android (Chrome):** open your torq address, tap **⋮** → **Add to Home screen** (or **Install app**).

You need a running [torq server](https://github.com/app-torq/torq#quick-start), or try the [demo](https://demo.torq-app.tech) first (user `demo`, password `password123`).

## What was planned

A native app for the things you do at the car: logging a service with photos from the camera, updating the odometer, working through a repair's parts list, reading the spec sheet offline, and local reminder notifications. It was to be built with React Native and Expo, with its API client generated from the server's [OpenAPI contract](https://github.com/app-torq/torq/blob/main/openapi.yaml), and distributed through AltStore PAL in the EU.

## License

[MIT](LICENSE)
