# Level 1 Header: Welcome to Web Scraping Test Page
by Dr Liang Jin

This is part of [Mini Python Programming Sessions](https://github.com/drliangjin/minipy).

## Level 2 Header (1): TODO

Part 1 **TODO** list:

- Inspect this page using Chrome's Developer Tool (right click mouse and select `Inspect`)
- Understand basic HTML structure such as `<head>`, `<body>`, `<header>`, `<div>` and `<h1>`
- Understand basic HTML tags such as `<p>`, `<a>`, and `<table>`
- Understand basic CSS properties such as `class` and `id`

Part 2 **TODO** list:

1. Scrape text contents
2. Scrape a table
3. Scrape a hyper link
4. Download a file

## Level 2 Header (2): Scraping

### Level 3 Header (1): Tables

| From                    | To                      | Press Alone                   | Device         |
|-------------------------|-------------------------|-------------------------------|----------------|
| <kbd> Command </kbd>    | <kbd> Option/Alt </kbd> | -                             | Apple Keyboard |
| <kbd> Option/Alt </kbd> | <kbd> Command </kbd>    | -                             | Apple Keyboard |
| <kbd> Caps Lock </kbd>  | <kbd> Ctrl </kbd>       | <kbd> ESC </kbd>              | -              |
| <kbd> Enter </kbd>      | <kbd> Ctrl </kbd>       | <kbd> Enter </kbd>            | -              |
| <kbd> Shift </kbd>      | <kbd> Shift </kbd>      | <kbd> ( </kbd> <kbd> ) </kbd> | -              |
| <kbd> Ctrl </kbd>       | <kbd> Hyper </kbd>      | <kbd> Caps Lock </kbd>        | -              |

### Level 3 Header (2): Documents
The following is a list of sample URLs you need to practice to go through
1. [txt file 1](docs/2012/test.txt)
2. [txt file 2](docs/2013/test.txt)
3. [txt file 3](docs/2014/test.txt)
4. [txt file 4](docs/2015/test.txt)
5. [txt file 5](docs/2016/test.txt)

Can you download all these files and write the Secret words to a new file (after `Secret:`)?

### Level 3 Header (3): How to do your first project to access non-commerical databases
To construct a new risk factor using textual analysis, first we need to harvest text data and then parse raw data from the internet (using web language) for further processing. In particular, we need a script to automate followings (suggestions for your coursework):
1. Start with the SEC Edgar's Archives for [directory listing of full-index](https://www.sec.gov/Archives/edgar/full-index/) and understand how SEC Edgar orgainse the U.S. companies' filings.
2. On the above index page, go to the directory for the year **2007** and choose one sub-directory, say **QTR4**.
3. Download the crawler.idx file and open it within Python (or if you want to have peek, you can open it up with any text editor).
4. Parse the useful information on the crawler files (for each QTR each Year) and store them individually with sensible file name.
5. Load up a crawler index file and access to the link for 10K page on SEC EDGAR database such as [this](https://www.sec.gov/Archives/edgar/data/320193/000032019318000145/0000320193-18-000145-index.htm)
6. On the 10K filing page, access the link to the actual filing in htm format (on the row when type == 10-K)
7. Harvest all the text data in the 10-K file and count words indicating financial constrains; store this info as an observation
8. Repeat this procedure for each company each quarter in the entire SEC EDGAR database (2007 to 2017 for data consistence) using loops, until you collect all the data needed to construct a new risk factor.
