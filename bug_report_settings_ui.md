
# Bug Report: UI Bug in Settings Page

- **Project**: Mozilla Firefox
- **Issue Title**: Misalignment of buttons on the Settings page
- **Issue Type**: UI Bug
- **Severity**: Medium

## Description:
Buttons on the Settings page become misaligned when the window is resized to a smaller width. This affects usability and the page's layout.

## Steps to Reproduce:
1. Open Firefox.
2. Go to Settings.
3. Resize the window to a width smaller than 800px.

## Expected Behavior:
Buttons should remain aligned, regardless of the window size.

## Actual Behavior:
Buttons overlap with other page elements.

## Environment:
- **OS**: Windows 10
- **Browser Version**: Mozilla Firefox 93.0

## Suggested Fix:
Adjust CSS media queries to maintain button alignment across different window sizes.
