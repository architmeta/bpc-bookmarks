# Bypass Paywalls Clean — Bookmarks

A categorized bookmark collection for websites supported by the **Bypass Paywalls Clean** ecosystem.

> **This is not a fork, extension, or replacement for Bypass Paywalls Clean.**
> It is a usability layer that makes the large number of websites in the BPC ecosystem easier to discover and navigate.

---

## What is Bypass Paywalls Clean?

[Bypass Paywalls Clean](https://gitflic.ru/project/magnolia1234/bypass-paywalls-clean-filters) is a project that provides filters and userscripts for websites that implement paywalls.

The BPC ecosystem covers a large number of newspapers, magazines, specialist publications and other websites across different countries and languages.

The filter-list project itself notes that the filter list does **not support as many sites as the full Bypass Paywalls Clean extension**, and that some supported sites require additional userscripts.

For current information about supported sites, filters and userscripts, always refer to the [original Bypass Paywalls Clean project](https://gitflic.ru/project/magnolia1234/bypass-paywalls-clean-filters).

---

## The problem

The sheer number of websites supported by Bypass Paywalls Clean is one of the best things about the project. But it also creates a usability problem. How is one supppose to track which websites are supported?

---

## The solution: bookmarks

This repository contains a browser-importable HTML bookmark file containing **400+ websites** associated with the Bypass Paywalls Clean ecosystem.

Rather than presenting these websites as one enormous list, I organized them into folders based primarily on **region and country**, with additional categories for different types of publications.

The idea is simple:

**Install Bypass Paywalls Clean → import these bookmarks → browse and discover publications.**

### Step 1 — Install Bypass Paywalls Clean

First, install and configure **[Bypass Paywalls Clean](https://gitflic.ru/project/magnolia1234/bypass-paywalls-clean-filters)** in your browser.

Follow the installation instructions provided by the upstream project:

**[→ Bypass Paywalls Clean installation instructions](https://gitflic.ru/project/magnolia1234/bypass-paywalls-clean-filters)**

> **Important:** This repository does not contain the BPC extension, filters, or userscripts. It only provides the bookmark collection.

### Step 2 — Import the bookmarks

Download **[`BPC-Bookmarks.html`](./BPC-Bookmarks.html)** from this repository.

You can either import it as-is or **edit the HTML file first** if you want to remove publications, add your own websites, or reorganize the categories.

Then import the HTML file using your browser's bookmark manager.

#### Brave

**[→ Brave: Import or export browsing data](https://support.brave.com/hc/en-us/articles/360019782291-How-do-I-import-or-export-browsing-data)**

Brave supports importing bookmarks from an HTML file. On desktop, open **Bookmarks → Bookmarks Manager → More options → Import**.

#### Chrome

**[→ Chrome: Import bookmarks and settings](https://support.google.com/chrome/answer/96816)**

Open **Bookmarks and lists → Import bookmarks and settings → Choose file**, then select `BPC-Bookmarks.html`. 

#### Firefox

**[→ Firefox: Import bookmarks from an HTML file](https://support.mozilla.org/en-US/kb/import-bookmarks-html-file)**

Open the Bookmarks Library and select **Import and Backup → Import Bookmarks from HTML**, then select the file.

#### Safari

**[→ Apple: Import bookmarks into Safari](https://support.apple.com/en-gb/guide/safari/ibrw1015/mac)**

Safari on Mac can import bookmarks from an HTML file exported by browsers such as Chrome, Firefox, and Edge. I’ve also managed to get BPC working on **iOS** by pairing [AdGuard](https://adguard.com/) with [Userscripts](https://apps.apple.com/app/userscripts/id1463298887), but the experience is more limited. **For the best experience, I recommend using Bypass Paywalls Clean on a desktop or laptop, preferably with a Chromium-based browser.**

#### Microsoft Edge

**[→ Microsoft: Import favorites and passwords in Edge](https://support.microsoft.com/en-us/edge/import-your-favorites-and-passwords-in-microsoft-edge)**

Go to **Settings → Profiles → Import browser data → Import browser data now**, then choose **Favorites or bookmarks HTML file**.

#### Arc

**[→ Arc: Import bookmarks, logins, history & extensions](https://resources.arc.net/hc/en-us/articles/19335089616791-Import-Bookmarks-Logins-History-Extensions-from-Your-Previous-Browser)**

Arc supports importing bookmarks from browsers including Chrome, Safari, Firefox, Brave and Edge. Go to **Arc → Import from Another Browser** and follow the prompts. 

> **Note:** Arc's official documentation describes importing from another browser rather than directly importing an arbitrary HTML bookmark file. If you want to use this collection in Arc, importing the HTML into a supported browser first and then importing that browser's bookmarks into Arc may be the easiest route.

### That's it

Once Bypass Paywalls Clean is installed and the bookmarks are imported, you can browse the collection from your browser and discover publications by country or region.

**You don't need to manually add the 400+ websites one by one.**

For example:

```text
BPC Bookmarks
│
├── 🇺🇸 USA
│   ├── Major Newspapers
│   ├── Business & Finance
│   ├── Tech & Science
│   ├── News Networks
│   └── Other Major Sites
│
├── 🇬🇧 United Kingdom
├── 🇫🇷 France
├── 🇩🇪 Germany
├── 🇨🇭 Switzerland
├── 🇮🇳 India
├── 🇨🇦 Canada
├── 🇦🇺 Australia / New Zealand
├── 🇯🇵 Japan
├── 🌎 Latin America
├── 🌏 Asia
└── 📰 Other Sites
