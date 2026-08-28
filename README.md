# Bypass Paywalls Clean — Bookmarks

A categorized bookmark collection for websites supported by the **Bypass Paywalls Clean** ecosystem.

> **This is not a fork, extension, or replacement for Bypass Paywalls Clean.**
> It is a usability layer that makes the large number of websites in the BPC ecosystem easier to discover and navigate.

---

## What is Bypass Paywalls Clean?

[Bypass Paywalls Clean](https://gitflic.ru/project/magnolia1234/bypass-paywalls-clean-filters) is a project that provides filters and userscripts for websites that implement paywalls.

The BPC ecosystem covers a large number of newspapers, magazines, specialist publications and other websites across different countries and languages.

The filter-list project itself notes that the filter list does **not support as many sites as the full Bypass Paywalls Clean extension**, and that some supported sites require additional userscripts. :contentReference[oaicite:1]{index=1}

For current information about supported sites, filters and userscripts, always refer to the [original Bypass Paywalls Clean project](https://gitflic.ru/project/magnolia1234/bypass-paywalls-clean-filters).

---

## The problem

The sheer number of websites supported by Bypass Paywalls Clean is one of the best things about the project.

But it also creates a usability problem:

**How do you actually find them?**

If you already know that a particular publication is supported, there is no problem — you visit the publication.

But if you are a journalist, researcher, student, or simply someone who reads publications from different countries, discovering what is available is much less intuitive.

The information surrounding BPC is primarily organized around:

- filter lists
- userscripts
- technical fixes
- domains
- implementation details

That makes sense for maintaining the project, but it isn't necessarily the easiest way for a reader to answer:

> **"What publications can I try?"**

I wanted a simple solution to that problem.

---

## The solution: bookmarks

The solution is deliberately simple:

**Bookmarks.**

This repository contains a browser-importable HTML bookmark file containing **400+ websites** associated with the Bypass Paywalls Clean ecosystem.

Rather than presenting the sites as one enormous list, the bookmarks are organized primarily by **region and country**, with additional categories for different types of publications.

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
