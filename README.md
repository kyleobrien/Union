# Union

A modern approach to [SBTM](https://en.wikipedia.org/wiki/Session-based_testing) documentation.

## The Format

The [Markdown](https://daringfireball.net/projects/markdown/) file is broken up into 4 sections:

-   The name and/or description of the system under test.
-   Metadata about the session.
-   Session notes. This is the heart of the document and describes your testing in as much detail as you require.
-   Other notes that don't directly apply to the session. These could contain your feelings about the system or some area that you think requires follow-up. This is designed as a catch-all.

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

Another [Union](https://en.wikipedia.org/wiki/Lake_Union).
