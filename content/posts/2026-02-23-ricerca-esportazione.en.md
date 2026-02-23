---
title: "Search and Export Issues Resolved: The Platform is Now Even Smoother!"
date: 2026-02-23T12:21:59+01:00
draft: false
cover:
    image: assets/images/new_color_logo.png
    imageDark: assets/images/new_white_logo_logo.png
    alt: "Platform Update"
    relative: false
---

Today we released a new update to make the platform even more stable and intuitive to use, especially when searching for and downloading information.

We identified and resolved two small "hiccups" that could occur during normal use:

### 1. Foolproof Excel Exports (even with no results)
Before today, if you tried to export an Excel file after running a search that produced no results (no data found), the system would crash and show a technical error. This happened because the "engine" that creates the Excel file stubbornly tried to insert columns into a completely empty sheet.

**What we did:** Now we have taught the system to handle these situations. If your search produces no results, the system will no longer crash, but will let you download a perfectly formatted Excel file containing only the header row, ready to be used.

### 2. Smarter Search for Compound Data (like "Name and Surname")
We noticed that, in some screens, when searching for specific keywords (for example, a worker's first or last name), the system would return zero results, even when the worker was actually present.

**What we did:** The problem was due to an overly rigid check in our internal search engine, which "ignored" fields created by merging multiple pieces of information (like the field that merges "Name" and "Surname"). We have removed this limit: now the search correctly "reads" combined data as well. This way, your searches will always be accurate and you will no longer risk ending up with empty screens for no reason.

---

We continue to work to make your daily work simpler and uninterrupted. Enjoy using the platform!
