# Time Drain Battery

**Time Drain Battery** is a lightweight web application that calculates and predicts how long your phone battery will last. It gives you a clear alert when your battery level drops to 15%. It works offline and is optimized for mobile users.

## Features

- Estimate shutdown time based on current battery percentage
- Animated buzzer + sound alert at 15% battery
- Works offline using a service worker
- Simple, clean UI for mobile and desktop
- Open source and easy to improve

## Live Demo

- [Visit on Netlify](https://timedrainbattery.netlify.app)
- [View on GitHub Pages](https://nibitanga-aime.github.io/Timedrainbattery-website-/)

## How It Works

- The app uses the `navigator.getBattery()` API to read your device's battery info
- It estimates time left based on current power level
- When battery hits 15%, it triggers a sound and visual alert
- Thanks to the service worker, you can use it without internet once it's loaded

## Installation (Offline or Local)

1. Clone this repository:
```bash
git clone https://github.com/nibitanga-aime/Timedrainbattery-website-.git
