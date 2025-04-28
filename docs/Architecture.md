Shield AdBlocker Architecture

Overview

Shield AdBlocker is a lightweight Chrome extension leveraging the Declarative Net Request (DNR) API to block ads and trackers. The architecture is designed to ensure simplicity, performance, and extensibility.

Key Components

1. Manifest File (manifest.json):

Defines the extension's metadata, permissions, and configurations.

Utilizes Chrome's Manifest V3 format.

2. Ruleset File (rules.json):

Contains JSON rules specifying ad-blocking logic.

Supports block actions with URL filters for common ad and tracker domains.

3. Icons:

PNG files in various sizes (16x16, 48x48, 128x128) for branding and display in the browser.

4. Background Service Worker (Optional):

May be added for advanced features, such as dynamic rule updates or user interaction logging.

Workflow

Initialization:

manifest.json registers the extension with Chrome.

DNR rules from rules.json are loaded and activated.

Ad Blocking:

Rules in rules.json are matched against network requests.

Matching requests are blocked based on the defined actions.

User Interaction (Optional):

Toolbar icons and popups can provide user feedback and customization options.

Future Extensions

Dynamic rules update mechanism.

User-customizable rulesets.

Localization support.