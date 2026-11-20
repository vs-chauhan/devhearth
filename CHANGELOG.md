# Changelog

All notable changes to DevHearth are listed here. Versions follow [Semantic Versioning](https://semver.org).

## [1.1.1]

- New flame app icon and in-app logo
- Warm orange colour theme to match the new brand
- Buttons now show their intended text colours (e.g. red Stop buttons)
- Fixed port numbers being cut off in Settings
- Tray icon renders correctly at small sizes

## [1.1.0] - first public release

- Apache **or** Nginx + PHP + MySQL 8.4 LTS, started and stopped with one click
- Every folder in `C:\DevHearth\www` is served at `https://<folder>.test` with a trusted local SSL certificate
- PHP 8.2 / 8.3 / 8.4 / 8.5, switchable; Composer included; PHP SSL bundle set up
- Laravel `public/` and Shopify PHP `web/public/` folders detected automatically
- Go apps: folders with a `go.mod` get a Run button and are proxied at `https://<folder>.test`
- phpMyAdmin at `https://phpmyadmin.test` with automatic login and one-click updates
- Per-project reverse proxy to Node / Remix / Shopify CLI dev servers (websockets supported)
- MySQL tuned for low memory use (~130 MB)
- Tray icon, start with Windows, log viewer, "terminal here", add php/composer/mysql/go to PATH
