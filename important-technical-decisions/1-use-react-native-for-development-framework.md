# Use React Native for the development framework

## The Problem

We need a mobile development framework for Tic Track that can build our
Tic Tac Toe game for Android within our course timeline.

## Options Considered

- **React Native**
- Ionic
- Cordova
- Framework7
- NativeScript

## Rationale

- React Native works well for building mobile applications and lets us
  create Tic Track for Android.
- React Native has strong documentation and community resources that will
  help the team during development.
- Our team is more familiar with JavaScript than the other frameworks, which will help reduce development time.
- The other frameworks were not selected because React Native has a larger community and more learning resources if we run into problems.

## Consequences
**Positive**
- Faster development because of reusable components.
- Large community support and good documentation.
- Easy to maintain as the project grows.

**Negative**
- Some native features require additional libraries.
- Team members who have not used React Native before will need some time to learn it.

## Notes

Target device (Android) and CSS framework (Bootstrap) were fixed constraints
set before this decision was made, not choices made by the team. React
Native renders native UI components rather than HTML/CSS, so it does not
directly use a CSS framework like Bootstrap, this is worth double-checking
with the instructor since the two decisions may be in tension.
