# Build your first Chrome Extension — HPTab

HPTab displays a beautiful Harry Potter inspired image from [Unsplash](https://unsplash.com) every time you open a new tab. This repo contains the complete code for the [HPTab tutorial] on building Chrome extensions. It is for reference only.

Here's what the completed project looks like:

![demo](https://github.com/keishabandz/HPTab/blob/main/demo.png)

## Setup

- Clone this repository to your filesystem:
```bash
git clone https://github.com/keishabandz/HPTab
```
- Create a free [Unsplash Developer account](https://unsplash.com/documentation#creating-a-developer-account) and [register](https://unsplash.com/documentation#registering-your-application) a new application.
- `cd` into the project folder. Open `js/background.js` and `js/popup.js` in your text editor.
- Replace `<your unsplash access key>` in both files with your Unsplash access key.
- Open Chrome, and open the Extensions page (`chrome://extensions/`). Ensure
developer mode is enabled
- Click "Load unpacked", and select the project folder, then click "Open".
- Open a new tab to see the extension interface.
