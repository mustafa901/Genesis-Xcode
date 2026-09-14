# Genesis

An iOS app by BioNeuraTech, built with SwiftUI.

## Project status

Early scaffold — currently the SwiftUI app template while core functionality is being designed.

- **Bundle ID:** `BioNeuraTech.Genesis`
- **Version:** 1.0 (build 1)
- **Deployment target:** iOS 16.2
- **Targets:** Genesis (app), GenesisTests (unit tests), GenesisUITests (UI tests)

## Building

Open `Genesis.xcodeproj` in Xcode and run the **Genesis** scheme.

> Note: App Store / TestFlight uploads require building with Xcode 26 / iOS 26 SDK or later (Apple requirement effective April 28, 2026). This repo is intended to build via **Xcode Cloud**, which uses Apple's cloud build machines.

## Roadmap to TestFlight

1. Connect this repo to Xcode Cloud (App Store Connect → Xcode Cloud)
2. Select a development team under Signing & Capabilities (paid Apple Developer Program)
3. Add a 1024×1024 app icon to `Assets.xcassets/AppIcon.appiconset`
4. Replace the template UI with the real app
5. Xcode Cloud archives and delivers builds to TestFlight automatically
