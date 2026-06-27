# Volume Guard Normalizer

Volume Guard normalizes the current tab audio using the Web Audio API.

## v0.2.8a highlights

- Connected the Report issue flow to GitHub Issues for `wnsdud820/volume-guard`.
- Added a popup **Copy diagnostics** button for quick support sharing.
- GitHub Issue drafts are prefilled with version, site, active state, gain, input-level, browser, language, and timestamp diagnostics.
- Added a GitHub repository button on the support page.
- Strengthened help guidance for negative dB values, waiting state, unsupported pages, and one-tab behavior.
- Added an update roadmap for v0.2.9, v0.3.0, and later growth features.
- No new permissions added.

## Version note

Chrome extension `version` remains `0.2.8` for manifest compatibility. The package uses `version_name: 0.2.8a` as the visible maintenance label.

## Support reporting

The extension does not auto-send reports. Users can copy a generated report template, copy diagnostics from the popup, or open a prefilled GitHub Issue draft from the support page.

## Permissions

- `tabCapture`: captures the current tab audio for local processing.
- `offscreen`: runs Web Audio processing in an offscreen document.
- `activeTab`: identifies the currently active tab when the user invokes the extension.
- `storage`: stores presets, output volume, site exclusions, and language settings locally.
