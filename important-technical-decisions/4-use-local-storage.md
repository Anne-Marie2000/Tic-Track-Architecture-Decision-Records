# Use Local Storage

## The Problem

We need to save simple information, like player scores, for Tic Track.

## Options Considered

- **Local Storage**
- Remote Database
- No Database

## Rationale

- Our app only needs to save simple information like player scores.
- We do not need a remote database because Tic Track does not have user
  accounts or online multiplayer.

## Consequences
**Positive**
- Easy to set up and maintain.
- No internet connection is required.
- Data can be loaded quickly.

**Negative**
- Data only exists on one device.
- Scores will be lost if the app is uninstalled or the device is reset.
- Players cannot sync their scores between devices.

## Notes

Scores are tied to a single device and will be lost if the app is
uninstalled or the device is reset — an acceptable trade-off given the
app's scope.
