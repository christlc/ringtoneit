# RingtoneIt - Ringtone Composer

A web-based RTTTL (Ringing Tone Text Transfer Language) ringtone composer that allows you to create and share nostalgic ringtones.

## Features

- **Interactive Ringtone Creation**: Create ringtones using RTTTL format
- **Preset Library**: Choose from popular tunes like "Ode to Joy", "Twinkle Twinkle", and "Für Elise"
- **Multiple Preview Styles**: Experience your ringtone with Retro, Phone, or Classic sound styles
- **Share & Download**: Share your creations or download them for use
- **Help Documentation**: Built-in guide explaining RTTTL format

## GitHub Pages

This application is automatically deployed to GitHub Pages using GitHub Actions. The deployment happens on:
- Push to main/master branch
- Pull requests to main/master branch 
- Manual workflow dispatch

### Files

- `index.html` - Main application file (default entry point for GitHub Pages)
- `.github/workflows/deploy-pages.yml` - GitHub Actions workflow for deployment

## Usage

Visit the GitHub Pages URL to use the application, or run locally by opening `index.html` in a web browser.

## Technology Stack

- HTML5
- CSS3 with Tailwind CSS
- JavaScript
- Tone.js for audio synthesis
- Inter font from Google Fonts

## RTTTL Format

RTTTL (Ringing Tone Text Transfer Language) is a simple text format for melodies, popularized in the late 1990s for mobile phone ringtones. The format consists of three parts separated by colons:

```
Title:Defaults:Notes
```

Example: `SimpleScale:d=4,o=5,b=120:c,d,e,f,g,a,b,c6`