# Volume Guard v0.2.7

## Stability + Bilingual Patch

- Added track-change guard to reduce loudness spikes when YouTube Music and similar sites move to the next song.
- Reduced excessive gain buildup during silence, fade-out, and low-level transition sections.
- Added Korean/English language toggle in the popup.
- Added Korean/English support for onboarding, issue report, and update history pages.
- Improved issue report template for GitHub Issues or manual support channels.
- Added manifest localization files for English and Korean.
- No new permissions added.

## Support reporting

Directly sending issue reports from an extension usually requires a backend server or an external API token, which is not recommended inside a distributed Chrome extension. v0.2.7 keeps reporting privacy-friendly: users can copy a generated report, and a GitHub Issues button can be enabled by setting `SUPPORT_CHANNELS.githubIssuesUrl` in `support.js`.
