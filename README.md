<p align="center"><img src="src/cover.gif" alt="SYMPHONY 8TH cover" width="480"></p>

# SYMPHONY 8TH

High-Res Photo Opener & Profile Gallery, packaged as a Windows 11 desktop app (Electron).

## Run locally
```
npm install
npm start
```

## Build the Windows installer
```
npm run dist
```
Outputs an installer (NSIS) and a portable `.exe` in `dist/`.

## Build on GitHub
Push this repo, then either run **Actions → Build Windows App → Run workflow**, or push a tag like `v1.0.0` to publish the `.exe` files to a Release.

## Icon
`build/icon.ico` is generated from `src/cover.gif` (cropped square). Replace it to change the app icon.
