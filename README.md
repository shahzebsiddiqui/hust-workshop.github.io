# hust-workshop.github.io

HUST Workshop at Supercomputing

## Layout of this repo

This site uses sections within a single page, where each page is particular year.
The sections come from the files in the `_posts` folder.
The date in the file name determines on which page the text will appear.

### Year Page

To create a page for all the sections of a single year, use the following (with the appropriate year):

```
---
layout: default
year: 20XX
---
```

### Page Sections

The sections of the page are posts within that year and appear in reverse-date order (oldest appear at the top).

The organization of the sections is:
- `20XX-01-01-intro.md`: Site intro.
- `20XX-01-02-program.md`: Workshop program.
- `20XX-01-05-dates.md`: Deadlines.
- `20XX-01-06-committes.md`: Names and institutions of the committee members.
- `20XX-01-07-slides.md`: Links to the presentation slides.
- `20XX-01-08-history.md`: Links to past websites.

Create or removed sections by changing  the files within the `_posts` directory. 

## Theme Source

This is a compressed-commit version of
[github.com/t413/SinglePaged](https://github.com/t413/SinglePaged)
