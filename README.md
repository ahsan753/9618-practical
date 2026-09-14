# 9618 Paper 4 — Practical Programming

Home-study lessons for Cambridge 9618 A Level Computer Science, Paper 4 (Practical),
Year 13 at United School International.

Each lesson is a single self-contained HTML page. Python runs in the browser via
Pyodide, loaded from jsDelivr — the only external dependency. If it cannot load,
the page falls back to "write it in your own IDE" and everything else still works.

## Structure

```
index.html          hub — lists every lesson
oop-lesson-1.html       20.1 OOP — Classes, Attributes and the Constructor
robots.txt          disallow all crawlers
```

Pages also carry `<meta name="robots" content="noindex, nofollow">`, so the site
is reachable by link but should not appear in search results.

## Adding a lesson

Add `oop-lesson-2.html` alongside the others, then add a card to the hub and
change its tag from `soon` to `live`.

The matching Evidence Document (.docx) for each lesson is issued through Teams,
not from here.
