# Volume Guard Normalizer

Volume Guard Normalizer is a Chrome extension that normalizes the audio of the current browser tab using the Web Audio API. When you enable the extension, it captures the active tab's audio and applies volume normalization locally in your browser, making loud videos quieter and quiet videos louder without affecting other tabs.

## Privacy policies

- [Official HTML privacy policy](./volume_guard_privacy_policy.html) — the full policy document used for Chrome Web Store submissions.
- Versioned policies for specific extension versions:
  - [v0.2.8a](./privacy-policies/v0.2.8a.md)
  - [v0.2.9](./privacy-policies/v0.2.9.md)
  - [v0.3.0](./privacy-policies/v0.3.0.md)

## Reporting bugs and support

Volume Guard does **not** automatically send bug reports or usage data. To report a problem:

1. Use the **Copy diagnostics** button in the extension popup or support page to copy a diagnostic template that includes version, site, active state, gain, input level, browser, language, and timestamp information.
2. Open a new GitHub Issue in this repository and paste the diagnostics or describe the issue. You can also open the prefilled GitHub Issue draft from the support page.
3. Review the diagnostics and remove any sensitive information before submitting. GitHub Issues are public, so do not post private data.

## Permissions

Volume Guard requests the following Chrome extension permissions:

| Permission | Purpose |
| --- | --- |
| `tabCapture` | Captures the audio of the active tab for local processing. |
| `offscreen` | Runs the Web Audio processing code in an offscreen document. |
| `activeTab` | Identifies the active tab when you invoke the extension. |
| `storage` | Stores presets, output volume, site exclusions, and language settings locally. |

## v0.2.8a highlights

- Connected the Report issue flow to GitHub Issues for `wnsdud820/volume-guard`.
- Added a popup **Copy diagnostics** button for quick support sharing.
- GitHub Issue drafts are prefilled with version, site, active state, gain, input level, browser, language, and timestamp diagnostics.
- Added a GitHub repository button on the support page.
- Strengthened help guidance for negative dB values, waiting state, unsupported pages, and one-tab behavior.
- Added an update roadmap for v0.2.9, v0.3.0, and later growth features.
- **No new permissions added.**

## Future versions

Volume Guard will continue to evolve. When new versions such as **v0.2.9**, **v0.3.0**, and later releases are prepared, their privacy policies will be added and maintained under the `privacy-policies/` folder in this repository.
