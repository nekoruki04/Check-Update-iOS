# iOS App Update Checker

This repository contains the version configuration file for iOS app update checks.

## 📋 About
- **File**: `version.json`
- **Purpose**: Remote version checking for iOS applications
- **Format**: JSON

## 🚀 How It Works
1. App requests `version.json` from this repository
2. Compares current app version with remote version
3. Shows update alert if newer version available

## 📁 File Format
```json
{
    "version": "1.0.0",
    "download_url": "https://example.com/app.zip"
}
