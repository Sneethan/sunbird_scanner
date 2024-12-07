
# Sunbird Scanner




![](https://cdn.thebeesnees.lol/scanner-banner.png)

## What does this do?

Sunbird Scanner is a custom built tool to scrape GoFundMe campaigns using [Puppeteer](https://pptr.dev/), and then reports campaign stats to a [Supabase](https://supabase.com/) table.

## Features

- Uses a loader script to support multiple tables
- Loads links directly from tables, using Supabase API
- Performant and fast
- Cross-platform


## Installation

Clone this project with the following command:

```bash
git clone https://github.com/Sneethan/sunbird_scanner
```
Create a file called ``.env`` and populate it with the following format of credentials, replacing URLHERE and KEYHERE with your credentials from the Supabase API dashboard for your project:

```
SUPABASE_URL=URLHERE
SUPABASE_ANON_KEY=KEYHERE
```

and ``index.js`` or other JS files if applicable with your table and column names. Then install dependencies with ``npm i`` and run ``node run.js`` to run the script!
    
## Acknowledgements

 - [Script made by Sneethan](https://sneethan.xyz)
 - [Databases made by Supabase](https://supabase.com/)
 - [Moral "support" by soft-sunbird](https://soft-sunbird.tumblr.com/) 

## Disclaimers

This code may break at any time if GoFundMe updates their site, and may have bugs and instablities. If you find bugs and know how to fix them, pull requests are very much appreciated.
