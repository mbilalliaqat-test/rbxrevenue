# PageSpeed ARIA Fix Report

Fixed issue: `Elements with an ARIA role that require children to contain a specific role are missing required children.`

The calculator tablist now has direct child buttons with `role="tab"` and matching panels with `role="tabpanel"`. Keyboard support was added for Arrow Left, Arrow Right, Home, and End.

- [x] tablist exists
- [x] tab roles exist
- [x] tabpanel roles exist
- [x] aria-selected exists
- [x] aria-controls exists
- [x] aria-labelledby exists
- [x] keyboard support exists
- [x] switchTab patched
