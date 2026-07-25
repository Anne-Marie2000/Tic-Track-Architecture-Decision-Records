# Use Stack Navigation

## The Problem

We need a navigation approach for Tic Track that lets users move easily
between the home screen, game screen, and other pages.

## Options Considered

- **Stack Navigation**
- Tab Navigation
- Drawer Navigation

## Rationale

- Tic Track will only have a few screens, so Stack Navigation is enough to
  let users move between the home screen, game screen, and other pages
  easily without added complexity.
- Tab Navigation and Drawer Navigation were not selected because they would add extra complexity that the app does not need.

## Consequences
**Positive**
- Easy to implement and maintain.
- Simple navigation for users.
- Works well for the current scope of the project.

**Negative**
- If many new screens are added later, another navigation style may be more suitable.
- Users cannot quickly jump between screens like they could with tabs.

## Notes

None.
