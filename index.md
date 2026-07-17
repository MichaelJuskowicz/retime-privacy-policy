---
title: Retime Privacy Policy
---

# Retime Privacy Policy

**Last updated: July 17, 2026**

Retime is a Chrome extension that converts timezone-aware times, time ranges, relative time phrases, and selected text into the user's chosen timezone.

## Data Retime Processes

Retime processes visible webpage text locally in your browser to identify time expressions such as `7 PM PDT`, `10:35–10:55 AM PDT`, or `12 hours ago`. When you use the context-menu converter, Retime also processes the text you selected. If Writing Mode is enabled, Retime may process time text in supported editable fields so it can preview and replace converted times.

Retime stores extension settings in Chrome storage, including:

- Preferred target timezone
- Additional tooltip timezones
- Time format preference
- Theme and accent color
- Site-access choices
- Abbreviation preferences
- Feature toggles such as automatic conversion, Writing Mode, and context-menu conversion

Chrome may sync these settings through the user's Chrome account when Chrome Sync is enabled. The developer of Retime does not receive or have access to this synced information.

## Data Sharing

Retime does not sell, rent, transmit, or share webpage text, selected text, personal communications, browsing content, or settings with the developer or third parties.

Retime does not use analytics, advertising, tracking pixels, remote logging, or remotely hosted code.

## Local Processing

Timezone conversion happens locally using browser-provided `Intl.DateTimeFormat` support and data bundled with the extension. Retime does not send text to a server for conversion.

## Permissions

Retime uses Chrome permissions only to provide its timezone-conversion features:

- **activeTab:** Runs conversion on the current tab after you ask Retime to convert it.
- **contextMenus:** Shows the "Convert selected time..." option when text is selected.
- **scripting:** Injects Retime's packaged content script and stylesheet into pages you activate or grant access to.
- **storage:** Saves extension settings and preferences.
- **Optional site access:** Enables automatic conversion on specific sites or all websites only after you grant access.

## Data Retention and Control

Retime settings remain in Chrome storage until you change them, reset Chrome Sync data, or uninstall the extension. You can change site-access lists and feature settings from the extension popup.

## Limited Use

Retime's use of information received from Chrome APIs complies with the Chrome Web Store User Data Policy, including the Limited Use requirements. Information is used only to provide Retime's user-facing timezone-conversion features.

## Contact

For privacy questions, contact [michaeljuskowicz@gmail.com](mailto:michaeljuskowicz@gmail.com).
