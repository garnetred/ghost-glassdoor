# Hide Slack Activity

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/decemberthedeveloper)

## Abstract
This Chrome browser extension does the following:
- hides the enable desktop notifications banner
- removes the "more unreads" buttons
- removes the activity badge app icon
- removes the slack activity button to hide the carousel of emojis
- removes the blur from posts older than 90 days
- allows users to click and read replies for posts older than 90 days
- un-truncates text in messages older than 90 days.

## Tech Stack
This project uses vanilla JS, CSS, and HTML.

## Setup/Installation
You can clone the repo locally using `git clone`.

[This article](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked) offers detailed instructions on loading an unpacked chrome extension. You can navigate to the chrome extensions page via the puzzle piece icon in the toolbar. Enable "developer mode" on the top-right. From there, you can click "load unpacked extension" and choose the folder via the popup. You should then see the Slack icon appear in the toolbar. When you click on it, you can see "Hide Slack Activity."

When you navigate to a Slack workspace website, you should no longer be prompted to enable desktop notifications if they're not enabled, see any badge icon indicating activity, or see the "more unreads" buttons. You should not see the Slack activity button. You should be able to see some posts older than 90 days and interact with them.

## Screenshots


## Future Changes
I'll port this extension to Firefox at some point.

## Attribution
Woman Detective favicon courtesy of [Google's Noto Emoji People Profession Icons iconpack](https://www.iconarchive.com/show/noto-emoji-people-profession-icons-by-google/10464-woman-detective-icon.html).

