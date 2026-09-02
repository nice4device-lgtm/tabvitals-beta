# TabVitals Beta

**The RAM Doctor for your browser.**

Find the tabs eating your memory.  
Sleep heavy tabs without closing anything.

[Official website](https://tabvitals.com/) · [Privacy](https://tabvitals.com/privacy) · [Security](https://tabvitals.com/security) · [Support](https://tabvitals.com/support)

## Official install (Chrome Web Store)

[Add to Chrome — Free (official)](https://chromewebstore.google.com/detail/tabvitals-%E2%80%94-tab-memory-fi/ljimhionelboehpfhipedoepaiiamdof)

Primary install path is now Chrome Web Store.  
Manual GitHub install is technical fallback only.
The canonical product website is [tabvitals.com](https://tabvitals.com/).

Current version: **V0.4.6 BETA**

Free during beta.

## What TabVitals does

- Finds memory-heavy Chrome tabs.
- Shows memory in MB and GB where Chrome provides the data.
- Lets you sleep heavy tabs without closing them.
- Keeps active, pinned, playing and Always Awake tabs protected.
- Fixes or resets one broken website without clearing unrelated browser sessions.
- Runs diagnostics locally.

## Install the beta

1. Open Chrome Web Store and click **Add to Chrome**.
2. Pin TabVitals to your toolbar if you want.
3. Open the extension and run your first X-Ray scan.

Manual fallback (if Web Store is blocked in your environment):

1. Download [TabVitals-v0.4.5-Beta-Chrome-Extension.zip](https://github.com/nice4device-lgtm/tabvitals-beta/releases/download/v0.4.5-beta/TabVitals-v0.4.5-Beta-Chrome-Extension.zip).
2. Unzip the downloaded file.
3. Open `chrome://extensions`.
4. Enable **Developer mode**.
5. Click **Load unpacked**.
6. Select the extracted TabVitals folder containing `manifest.json`.
7. Pin TabVitals to the Chrome toolbar if desired.
8. Run your first X-Ray scan.

## Privacy

TabVitals does not upload:

- passwords;
- cookies;
- page content;
- browsing history.

Diagnostics run locally on the user's computer.

## Security

Chrome may show a diagnostics/debugger warning because TabVitals uses Chrome's debugging interface to measure tab and process diagnostics during an X-Ray scan. The connection is temporary and used only while diagnostics run.

No page content, passwords, cookies, or browsing history are uploaded.

## Install path details

- CWS version: `V0.4.6 BETA`
- GitHub fallback ZIP: `V0.4.5 BETA` (manual install only)
- File: `TabVitals-v0.4.5-Beta-Chrome-Extension.zip`
- SHA-256: `5be82bc8fb6dbe54f38aae23ef9d2d1bd4a102a7f518f254bba05ba278c9981d`

[Technical fallback release (v0.4.5)](https://github.com/nice4device-lgtm/tabvitals-beta/releases/tag/v0.4.5-beta)

[Creator test kit](CREATOR_TEST_KIT.md)

This repository is the **technical fallback** distribution channel for manual installation when Google Web Store is blocked.
The extension source code is not published here.
