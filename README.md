# Ghost Glassdoor

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/decemberthedeveloper)

## Abstract

This browser extension for Chrome and Firefox allows users to access Glassdoor without having to login.

Note: This extension has _not_ been tested with all of the country domains used by Glassdoor - please open an issue if there's a problem with a specific country's website.

## Background

In March 2024, Glassdoor users learned that the site [now requires them to use their real names](https://www.wired.com/story/glassdoor-wants-to-know-your-real-name/) - even going so far as to using external information to match users with a possible name. Some users have also run into issues trying to delete their account. This extension at least gives users the option of not having to reveal their identities or create a decoy account to browse the site. You'll still need to log in to post reviews or update your profile info.

## Tech Stack

This project uses vanilla JS, CSS, and HTML.

## Setup/Installation

You can clone the repo locally using `git clone git@github.com:garnetred/ghost-glassdoor.git`.

Without using a terminal you can also visit the project homepage, select the green button that says "code" and then click the option to "Download zip." From there you'll need to unzip the folder before following the rest of the instructions.

### Chrome (and other Chromium-based browsers)

[This article](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked) offers detailed instructions on loading an unpacked chrome extension. You can navigate to the chrome extensions page via the detective icon in the toolbar. Enable "developer mode" on the top-right. From there, you can click "load unpacked extension" and choose the folder via the popup. You should then see the detective icon appear in the toolbar. When you click on it, you can see a popup that reads "Ghost Glassdoor."

When you navigate to Glassdoor, you should be able to browse the site like normal without having to log in or register.

### Firefox

You can go to about:addons and select the gear icon. From there, you can install the extension from a file and select the .xpi file located in the `web-ext-artifacts` folder within the `ghost-glassdoor` folder. There may be a popup asking about browser tab permissions, and you can click yes or accept. Then if you go to Glassdoor, you should see the extension requesting access to the page, which you can enable.

After this, when you go to different pages on the Glassdoor website, you should be able to access the page without logging in or registering.

## Future Changes

At some point it would be nice to investigate the flickering effect on Firefox with the login box and fix it.

## Attribution

Woman Detective favicon courtesy of [Google's Noto Emoji People Profession Icons iconpack](https://www.iconarchive.com/show/noto-emoji-people-profession-icons-by-google/10464-woman-detective-icon.html).
