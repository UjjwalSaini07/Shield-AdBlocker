# Shield-AdBlocker
Shield AdBlocker is a Chrome extension designed to block unwanted ads and trackers using the **declarativeNetRequest** API in Chrome's Manifest V3. By applying predefined rules to known ad-serving domains, it ensures a faster, cleaner, and more secure browsing experience, free from intrusive ads and tracking technologies.

[![Github License](https://img.shields.io/github/license/UjjwalSaini07/Shield-AdBlocker)](https://github.com/UjjwalSaini07/Shield-AdBlocker/blob/main/LICENSE)
[![Info](https://img.shields.io/badge/Project-Info-blue?style=flat&logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iaXNvLTg4NTktMSI/Pg0KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPg0KPHN2ZyB2ZXJzaW9uPSIxLjEiIGlkPSJDYXBhXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSIwIDAgNTEyIDUxMiIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgNTEyIDUxMjsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHBhdGggc3R5bGU9ImZpbGw6IzBBNEVBRjsiIGQ9Ik0yNTYsNTEyYy02OC4zOCwwLTEzMi42NjctMjYuNjI5LTE4MS4wMi03NC45OEMyNi42MjksMzg4LjY2NywwLDMyNC4zOCwwLDI1Ng0KCVMyNi42MjksMTIzLjMzMyw3NC45OCw3NC45OEMxMjMuMzMzLDI2LjYyOSwxODcuNjIsMCwyNTYsMHMxMzIuNjY3LDI2LjYyOSwxODEuMDIsNzQuOThDNDg1LjM3MSwxMjMuMzMzLDUxMiwxODcuNjIsNTEyLDI1Ng0KCXMtMjYuNjI5LDEzMi42NjctNzQuOTgsMTgxLjAyQzM4OC42NjcsNDg1LjM3MSwzMjQuMzgsNTEyLDI1Niw1MTJ6Ii8+DQo8cGF0aCBzdHlsZT0iZmlsbDojMDYzRThCOyIgZD0iTTQzNy4wMiw3NC45OEMzODguNjY3LDI2LjYyOSwzMjQuMzgsMCwyNTYsMHY1MTJjNjguMzgsMCwxMzIuNjY3LTI2LjYyOSwxODEuMDItNzQuOTgNCglDNDg1LjM3MSwzODguNjY3LDUxMiwzMjQuMzgsNTEyLDI1NlM0ODUuMzcxLDEyMy4zMzMsNDM3LjAyLDc0Ljk4eiIvPg0KPHBhdGggc3R5bGU9ImZpbGw6I0ZGRkZGRjsiIGQ9Ik0yNTYsMTg1Yy0zMC4zMjcsMC01NS0yNC42NzMtNTUtNTVzMjQuNjczLTU1LDU1LTU1czU1LDI0LjY3Myw1NSw1NVMyODYuMzI3LDE4NSwyNTYsMTg1eiBNMzAxLDM5NQ0KCVYyMTVIMTkxdjMwaDMwdjE1MGgtMzB2MzBoMTQwdi0zMEgzMDF6Ii8+DQo8Zz4NCgk8cGF0aCBzdHlsZT0iZmlsbDojQ0NFRkZGOyIgZD0iTTI1NiwxODVjMzAuMzI3LDAsNTUtMjQuNjczLDU1LTU1cy0yNC42NzMtNTUtNTUtNTVWMTg1eiIvPg0KCTxwb2x5Z29uIHN0eWxlPSJmaWxsOiNDQ0VGRkY7IiBwb2ludHM9IjMwMSwzOTUgMzAxLDIxNSAyNTYsMjE1IDI1Niw0MjUgMzMxLDQyNSAzMzEsMzk1IAkiLz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjxnPg0KPC9nPg0KPGc+DQo8L2c+DQo8Zz4NCjwvZz4NCjwvc3ZnPg0K)](https://github.com/UjjwalSaini07/Shield-AdBlocker/blob/main/README.md)
[![Generic badge](https://img.shields.io/badge/Owner-@UjjwalS-<COLOR>.svg)](https://github.com/UjjwalSaini07/Shield-AdBlocker)
[![GitHub stars](https://img.shields.io/github/stars/UjjwalSaini07/Shield-AdBlocker?style=social&label=Star&maxAge=2592100)](https://github.com/UjjwalSaini07/Shield-AdBlocker)
[![Github Release](https://img.shields.io/github/v/release/UjjwalSaini07/Shield-AdBlocker)](https://github.com/UjjwalSaini07/Shield-AdBlocker)

## Features

- 🚫 Blocks ads from popular ad-serving domains such as:
  - doubleclick.net, googleadservices.com, googlesyndication.com, youtubeads.googleapis.com, facebook.com/ads/, twitter.com/ads, amazon-adsystem.com, bing.com/ad.
- ⚡ Utilizes Chrome's efficient declarativeNetRequest API for improved performance and security.
- 🔧 Easy to configure and extend by modifying the rules.json file.
- 🔒 Enhances privacy by preventing tracking scripts from loading.
- 🚀 Provides a faster and smoother browsing experience by reducing page load times.

## Project Structure
```
📂 Shield-AdBlocker-rootDir
├── 📂 docs
│   └── 📄 Architecture.md
├── 📂 icons
│   ├── 🖼️ icon24.png
│   ├── 🖼️ icon48.png
│   ├── 🖼️ icon128.png
│   └── 🖼️ MainLogo.png
├── 📄 CHANGELOG.md
├── 📄 LICENSE
├── 📄 manifest.json
├── 📄 messages.json
├── 📄 README.md
├── 📄 rules.json
```

## How It Works

1. 📜 The `manifest.json` file configures the extension by enabling the `declarativeNetRequest` API, which is responsible for blocking ads. It also points to the `rules.json` file, which contains the rules for ad-blocking.
2. 📝 The `rules.json` file holds a list of ad-blocking rules, each defining a URL pattern (e.g., `doubleclick.net`) that should be blocked to prevent ads and trackers from loading.
3. 🚫 Once the extension is loaded in Chrome, it automatically applies the rules from `rules.json`, blocking any network requests that match the specified patterns, ensuring a cleaner and faster browsing experience.
4. ⚡ The `declarativeNetRequest` API processes the rules efficiently in the background, minimizing performance overhead while providing a seamless experience for users.
5. 🔧 The extension is highly configurable, allowing you to easily add, remove, or modify rules in the `rules.json` file, making it customizable to fit your ad-blocking needs.

## Installation

- First Read this [License](https://github.com/UjjwalSaini07/Shield-AdBlocker/blob/main/LICENSE) & their terms then proceed.
- Star ⭐ the [Repository](https://github.com/UjjwalSaini07/Shield-AdBlocker)

1. 🧑‍💻 Clone or download this repository to your local machine.
```bash
    git clone https://github.com/UjjwalSaini07/Shield-AdBlocker.git
```
2. 🌐 Open Chrome and go to chrome://extensions/ in the address bar.
3. Enable **"Developer mode"** by toggling the switch in the top-right corner of the Extensions page.
4. Click on **"Load unpacked"** and select the project folder where the extension files are stored.
5. 🚀 The extension will now be loaded into Chrome, and ads matching the rules in `rules.json` will be automatically blocked.
6. 🔄 Test the extension by visiting websites with known ads or trackers to see it in action.
7. ⚙️ Configure the extension by modifying the `rules.jso`n file for custom ad-blocking preferences.
8. 🛠️ Update and maintain the extension by loading new versions with any changes you make to the project folder.

## Customization

To add or modify blocking rules:

1. Open the `rules.json` file in your preferred text editor.
2. Add a new rule object, specifying the `id`, `priority`, `action`, and `condition` for the rule.
3. Save the changes to the file.
4. Reload the extension in Chrome by going to `chrome://extensions/` and clicking the "Reload" button on your extension card.
5. Test your changes by visiting websites that should be affected by the new rules to ensure proper functionality.
6. Modify existing rules by adjusting their `priority`, `condition`, or `action` as needed to refine the blocking process.
7. You can also remove rules by deleting specific rule objects from `rules.json` to stop blocking particular domains.
8. For advanced customization, consider combining multiple conditions or actions, such as blocking multiple domains or applying different actions (e.g., redirecting requests).
9. Ensure that the `id` of each rule is unique to avoid conflicts and maintain smooth rule processing.
10. Once you're satisfied with the changes, you can share your custom rules by exporting the `rules.json` file, allowing others to benefit from your configuration.

## Example Rule Set

```json
{
    "id": 8,
    "priority": 1,
    "action": { "type": "block" },
    "condition": { "urlFilter": "*://*example-ad-domain.com/*" }
}
```

## Contact 📞
Feel free to reach out if you have any questions or suggestions!

- Raise an issue for the same [Issue](https://github.com/UjjwalSaini07/Shield-AdBlocker/issues)
- Github: [@Ujjwal Saini](https://github.com/UjjwalSaini07)

## Feedback and Contributions 💌
Feedback and contributions are always welcome! Feel free to open an [Issue](https://github.com/UjjwalSaini07/Shield-AdBlocker/issues).

<div align="center">
    <a href="#top">
        <img src="https://img.shields.io/badge/Back%20to%20Top-000000?style=for-the-badge&logo=github&logoColor=white" alt="Back to Top">
    </a>
</div>
