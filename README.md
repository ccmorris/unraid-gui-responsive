# unraid-gui-responsive

> Responsive design for the Unraid GUI

## Installation

1. Install the `Theme Engine` plugin in Unraid
2. Open the Theme Engine settings, from the Unraid Settings page
3. Toggle from `Basic view` to `Advanced view`
4. Set `Enable custom styling` to `Yes`
5. Copy and paste the following code into the `Custom styling (advanced)` field:
```html
</style>
<link type="text/css" rel="Stylesheet" href="https://rawcdn.githack.com/dohnutt/unraid-gui-responsive/refs/heads/main/custom.css" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
```
6. Click apply
7. Enjoy from your phone/tablet

## Why does this exist?

These style overrides exist because the Unraid GUI does not have a responsive design, making it painful to use from a phone/tablet.

## Strategy

- Avoid modifying the desktop layout so that the design will never become completely broken
- Avoid use of colour
- Use the minimum amount of changes
- Expect breaking changes upstream

## Known issues

Last tested with Unraid OS v6.12.8.

- Some tables are too large and require scrolling left/right, eg. devices on the `Main` page
- Tabs layout does not work
- Footer statusbar is gone
- Scrolling issues on the `Main` page on touch devices
- Certainly more... Please tell me, or submit a pull request!

## Next steps

- Collect bug reports from more users
- See if it is possible to contribute to the [official Unraid theme dynamix](https://github.com/limetech/webgui/tree/master/plugins/dynamix)
