# TextReplacer Updates Distribution

This repository hosts the update distribution infrastructure for TextReplacer macOS app.

## Structure

- **GitHub Releases**: Contains signed DMG files for each version
- **GitHub Pages** (`gh-pages` branch): Hosts the Sparkle appcast.xml file

## Auto-Update URLs

- **Appcast**: https://leixusam.github.io/promptflow-updates/appcast.xml
- **Downloads**: https://github.com/leixusam/promptflow-updates/releases/

## Automated Updates

This repository is automatically updated by GitHub Actions from the private development repository whenever a new release is tagged.