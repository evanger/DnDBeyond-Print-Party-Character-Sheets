# D&D Beyond Live-Update Campaign Page

 ![Static Badge](https://img.shields.io/badge/JavaScript-x?style=plastic&logo=javascript&color=%235b5b5b)

![Live Update Campaign Page Splash](./images/live-update-campaign-print.png)

**D&D Beyond Live-Update Campaign Page** is a script that allows you to view live data about each of the characters in a D&D Beyond campaign from the Campaign page itself, modified to also allow for printing the entire party on simplified character sheets.

- [D\&D Beyond Live-Update Campaign Page](#dd-beyond-live-update-campaign-page)
  - [1. Prerequisites](#1-prerequisites)
  - [2. How to Install and Set-up](#2-how-to-install-and-set-up)
  - [3. How to Use](#3-how-to-use)
  - [4. What does it look like?](#4-what-does-it-look-like)
  - [5. Credits](#5-credits)
  - [6. License](#6-license)
  - [7. Version Notes](#7-version-notes)
    - [v 1.2](#v-12)
    - [v 1.1.1](#v-111)
    - [v 1.1](#v-11)

## 1. Prerequisites

To use this script, you will need a browser extension that allows you to run User Scripts. There a numerous available to choose from, including:

| Extension | Browser Support |
| --- | --- |
| [Firemonkey](https://addons.mozilla.org/en-US/firefox/addon/firemonkey/) | ![Firefox](./images/icon-firefox.png) |
| [Greasemonkey](https://www.greasespot.net/) | ![Firefox](./images/icon-firefox.png) |
| [Tampermonkey](https://www.tampermonkey.net/) | ![Chrome](./images/icon-chrome-18.png) ![Edge](./images/icon-edge.png) ![Firefox](./images/icon-firefox.png) ![Opera Next](./images/icon-opera.png) ![Safari](./images/icon-safari.png) |
| [Violentmonkey](https://violentmonkey.github.io/) | ![Chrome](./images/icon-chrome-18.png) ![Edge](./images/icon-edge.png) ![Firefox](./images/icon-firefox.png) |

Install one of these extensions for your browser. If you're not sure, I recommend Tampermonkey.

## 2. How to Install and Set-up

Ensure you are running a browser extension that takes UserScripts (see Prerequisites above).

Click on the Install Script button below to install this user script to your browser extension, then follow the instructions from your browser extension.

[![Live Update Campaign Page Splash](./images/install-button.png)](https://github.com/evanger/DnDBeyond-Live-Campaign-Print-Party-Character-Sheets/raw/master/ddb-live-campaign-print.user.js)

## 3. How to Use

1. Open your [campaigns page on the D&D Beyond website](https://www.dndbeyond.com/my-campaigns).
2. Click on one of your campaigns.

You'll now see additional information displayed on the card of each character, showing:

- Current Hit Points
- Current Armor Class
- Ability Scores
- Passive Perception / Investigation / Insight

The data is automatically updated every 60 seconds.

You will also see a "Print Party" button which will generate a new, simplified two-page character sheet for each party member. You can select the accent color for the character sheets. This new simplified sheet is based on that used on D&D Beyond for the D&D cartoon sample characters.

![Live Update Campaign Page Splash](./images/sheet_sample.png)

## 4. What does it look like?

This is how the character cards on the campaign page look with this script running.

![Live Update Campaign Page Splash](./images/after_mods.png)

## 5. Credits

Author: [Faith Elisabeth Lilley](https://github.com/FaithLilley) (aka Stormknight) and [Brent Evanger](https://github.com/evanger)

Contributors: [@xander-hirst](https://github.com/xander-hirst)

Project forked from [DNDBeyond-Live-Campaign](https://github.com/FaithLilley/DnDBeyond-Live-Campaign/) by [Faith Elisabeth Lilley](https://github.com/FaithLilley) (aka Stormknight)

Which was forked from [DNDBeyond-DM-Screen](https://github.com/TeaWithLucas/DNDBeyond-DM-Screen) by [TeaWithLucas](https://github.com/TeaWithLucas) - huge thanks for figuring out the DDB API code.

## 6. License

This project uses the [MIT license](LICENSE.md).

## 7. Version Notes

### v 1.2

Modified version of Live Campaign featuring the "Print Party" button

### v 1.1.1

Fix due to version change of the DDB API libraries. Thanks Xander!

### v 1.1

First full release.
