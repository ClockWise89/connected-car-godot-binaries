# ConnectedCar Godot Binaries

Release artifacts for ConnectedCar Godot binaries (`libgodot.xcframework.zip`).

## Tag convention

Use iOS-focused tags:

- `ios-4.5.1`
- `ios-4.6.0`
- `ios-4.6.1`
- `ios-4.6.1-r1`
- `ios-4.6.1-r2`
- `ios-4.6.1-r3`
- `ios-4.6.1-r4`
- `ios-4.6.1-r5`

Use `-rN` suffixes for republished artifacts under the same Godot engine version when binary packaging/build flags change.

## Asset convention

Each release should include:

- `libgodot.xcframework.zip`

Release notes should include the SPM checksum so `connected-car-godot-ios` can update `Package.swift`.

## Current recommended release

- `ios-4.6.1-r5`
