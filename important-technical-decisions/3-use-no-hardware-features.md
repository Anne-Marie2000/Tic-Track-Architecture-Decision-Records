# Use no hardware features

## The Problem

We need to decide which device hardware, if any, Tic Track should use.

## Options Considered

- GPS
- Speaker
- Camera
- Fingerprint Scanner
- **No Hardware Features**

## Rationale

- Tic Track does not need any hardware features. The game can work using
  only the touchscreen, so features like GPS, camera, and fingerprint
  scanning are not needed.

## Consequences
**Positive**
- No special device permissions are required.
- Development is simpler.
- The app is easier to test on different Android devices.

**Negative**
- Future features that depend on hardware would require changes to the app architecture.
## Notes

None.
