# Praxis SDK for iOS

The Swift Package Manager distribution of `PraxisSDK`, which makes an iOS app hands-free and verified with Praxis.

This repository holds only the package manifest and release notes. The SDK itself is a binary XCFramework attached to each release and pinned by checksum in `Package.swift`; its source is built and published from the Praxis repository's CI.

## Status

No release yet. The first pre-release (`0.1.0-alpha.1`) will add `Package.swift` here. Until then there is nothing to install.

## Installing (from the first release)

In Xcode, choose File › Add Package Dependencies and enter:

```
https://github.com/SilkRoute-AI/praxis-sdk-ios
```

Then add the `PraxisSDK` library to your app target.

## Versions

The iOS SDK and the Android SDK (`ai.getpraxis:praxis-sdk` on Maven Central) share one version number and expose the same calls.

More at [getpraxis.ai](https://getpraxis.ai).
