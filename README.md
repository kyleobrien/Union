# Union

Exploratory testing with [SBTM](https://en.wikipedia.org/wiki/Session-based_testing) and Markdown.

## Background

TODO!

The key feature of this format is that it prefers convention over new syntax. In this way, readily available markdown processing tools already work. Adhereing to convention *might* enable additional functionality at a later time.

## File Format

The [Markdown](https://daringfireball.net/projects/markdown/) file is broken up into 4 sections:

-   The name and/or description of the system under test.
-   Metadata about the testing session.
-   Your session notes. This is the heart of the document and describes your testing in as much detail as you require.
-   Other notes that don't explicitly relate to the your testing session, but are still important. These could contain your feelings about the system or some area that you think requires follow-up. This is designed as a catch-all.

## Conventions

### Metadata

-   The "Testers" and "Tags" fields are comma-separated strings.
-   The prefered format for the "Start" and "Stop" fields is YYYY.MM.DD HH:MM, but any format that's parsable by a programming language will work.

### Session Notes

-   Notes are taken in an outline format.
-   Indicate bugs and issues with strong emphasis, using double asteriks.
-   Indicate interesting, peculiar and follow-up issues with emphasis, using a single asterik.
-   Immediately following your single or double asteriks, include a parenthesis wrapped timestamp. This helps put the item in context within the exploratory session.
-   Add screenshots with an alt-text string that starts with "Screenshot: "
-   Link issues that are filed in a big tracker with a reference-style link.

## Miscellaneous

The charter template is taken from Elisabeth Hendrickson's excellent book [Explore It!](http://a.co/aAVo6CV).

There's a [Trello Project Board](https://trello.com/b/F8GEZdSW/union) for this thing.

Another [Union](https://en.wikipedia.org/wiki/Lake_Union).
