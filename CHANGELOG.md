# Changelog

## v1.1.5

- Fix an issue where spaces were being passed as children when not asked for. This would result in using things like <Pause> inserting a space!

## v1.1.4

- Fixes a bad publish.

## v1.1.3

- Export `StyledText` from entry index

## v1.1.2

- Update the break-styled-lines dependency to fix a regression in Linebreaker.

## v1.1.1

- Update a few deps for security fixes

## v1.1.0

- Added a `StyledText` component to be used with `Linebreaker`. Use this if you have differently styled text within a single `Linebreaker` usage.
- `useWindupString` will now display the current string value in React devtools