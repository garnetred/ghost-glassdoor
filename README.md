# Ghost Glassdoor

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/decemberthedeveloper)

## Abstract

This Chrome browser extension allows users to accesss Glassdoor without having to login.
Note: This extension has not been tested with all the country domains - please open an issue if there's a problem with a specific country's website.

## Background

In March 2024, Glassdoor users learned that the site [now requires them to use their real names](https://www.wired.com/story/glassdoor-wants-to-know-your-real-name/) - even going so far as to using external information to match users with a possible name. Some users have also run into issues trying to delete their account. This extension at least gives users the option of not having to reveal their identities or create a decoy account to browse the site. You'll still need to log in to post reviews or update your profile info.

## Tech Stack

This project uses vanilla JS, CSS, and HTML.

## Setup/Installation

You can clone the repo locally using `git clone`.

[This article](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked) offers detailed instructions on loading an unpacked chrome extension. You can navigate to the chrome extensions page via the puzzle piece icon in the toolbar. Enable "developer mode" on the top-right. From there, you can click "load unpacked extension" and choose the folder via the popup. You should then see the detective icon appear in the toolbar. When you click on it, you can see a popup that reads "Ghost Glassdoor."

When you navigate to Glassdoor, you should be able to browse the site like normal without having to log in or register.

## Future Changes

I'll port this extension to Firefox at some point.

## Attribution

Woman Detective favicon courtesy of [Google's Noto Emoji People Profession Icons iconpack](https://www.iconarchive.com/show/noto-emoji-people-profession-icons-by-google/10464-woman-detective-icon.html).
