# Union

Exploratory testing with [SBTM](http://www.satisfice.com/sbtm/) and [Markdown](https://daringfireball.net/projects/markdown/).

## Overview

Union is a simple, formatted outline that favors convention over new syntax. In this way, your testing documentation can take advantage of popular text editors and existing Markdown tools to display your notes in the way that is right for you.

## File Format

The Markdown file is broken up into 4 sections:

| Section                | Description                                                                                                         |
| :--------------------- | :------------------------------------------------------------------------------------------------------------------ |
| YAML Header (Metadata) | The who, what, why, when and how of the session. You can even add your own fields!                                  |
| Name / Description     | A high-level, one sentence description of the thing you're testing in the session.                                  |
| Notes                  | The heart of the document; describes your testing in as much detail as you require.                                 |
| Debrief                | Notes from discussions with test managers or fellow testers about the content of the session.                       |

## Conventions

### YAML Header (Metadata)

-   The "Testers" and "Tags" fields are comma-separated strings.
-   The prefered format for the "Start" and "Stop" fields is YYYY-MM-DD HH:MM, but any format that's easily parsable by a programming language is appropriate.

### Notes

-   Notes are taken in an outline format.
-   Indicate bugs with strong emphasis, using double asteriks or double underscores.
-   Indicate issues (problems or observations that require investigation) with emphasis, using single asteriks or single underscores.
-   Include a parenthesis wrapped timestamp when noting bugs and issues. This helps put the item in context within the testing session. See the [template](.//template.md) for examples.
-   Link issues that are filed in a bug tracker with a reference-style link.

## Miscellaneous

The charter template is from Elisabeth Hendrickson's excellent book [Explore It!](https://pragprog.com/titles/ehxta/explore-it/).

There's a [Trello Project Board](https://trello.com/b/F8GEZdSW/union) for this thing.

Another [Union](https://en.wikipedia.org/wiki/Lake_Union).
