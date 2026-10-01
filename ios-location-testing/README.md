# iOS Location Testing

This folder contains **safe, Apple-supported** location-simulation assets for testing apps you own or are authorized to test.

## Files

- `TestPoint.gpx` — one fixed test location.
- `TestRoute.gpx` — a short multi-point test route.
- `LocationUITests.swift` — a minimal XCUITest example using a simulated location.

## Use with Xcode

### Fixed point / route with GPX

1. Open your iOS project in Xcode.
2. Add the GPX file to the project/workspace.
3. Run your app on Simulator or a connected development device.
4. Choose the GPX file as the simulated location in the Scheme/Test Plan or Debug location controls.
5. Verify your app's Core Location / MapKit behavior.

### UI test example

The Swift file demonstrates how to set a software-simulated location from XCUITest.

## Notes

- These files are intended for **your own app testing**.
- They do not alter GNSS/GPS hardware signals.
- Apps can detect software-simulated locations via Core Location source information.
- Replace the example coordinates with your own test coordinates as needed.
