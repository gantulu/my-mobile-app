# My Mobile App

React + Vite + TypeScript application with Capacitor for Android and iOS.

## Requirements
- Node.js 20.19+ or 22.12+
- npm
- Android Studio for Android builds
- Xcode on macOS for iOS builds

## Setup
1. Run `npm install`.
2. Copy `.env.example` to `.env`.
3. Run `npm run dev`.

## Build
Run `npm run build` to generate the web app in `dist/`.

## Native platforms
Run `npx cap add android` and `npx cap add ios` once the required native toolchains are installed. iOS builds require macOS and Xcode.

Then run `npm run cap:sync` to build and sync web assets. Use `npm run cap:android` or `npm run cap:ios` to open the native project.

## Source layout
- `assets/`: images, icons, fonts
- `components/`: reusable UI components
- `features/`: feature modules
- `hooks/`: shared React hooks
- `layouts/`: app layouts
- `pages/`: route-level screens
- `services/`: API integrations
- `styles/`: global styles and tokens
- `types/`: shared TypeScript types
- `utils/`: utilities

Capacitor generates the `android/` and `ios/` native projects; commit them after platform setup.
