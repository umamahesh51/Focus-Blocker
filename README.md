# Focus Blocker - Chrome Extension (MV3)

Block distracting websites and stay in flow. Add your own list, enable/disable quickly, snooze temporarily, and get a motivational quote whenever a site is blocked.

## Features
- Block list using Declarative Net Request (MV3)
- Snooze temporarily (auto-resume when time's up)
- Motivational quotes on the blocked page
- Options page to add/remove sites and manage quotes
- CSP-friendly: no inline scripts/styles

## Permissions
- storage - save your settings (blocklist, quotes, toggles)
- declarativeNetRequest - block navigation to configured domains
- alarms - resume blocking automatically after snooze ends
- host_permissions - set to <all_urls> to allow redirect rules; can be narrowed if you prefer

## Local-Only Data
All settings are stored via chrome.storage. No external servers are contacted.

## Development
1. Open chrome://extensions
2. Enable Developer mode
3. Load unpacked -> select the extension/ directory

## Packaging
Upload the extension/ folder's contents as your store build (or zip the folder). This package includes store listing assets under store-listing/.
