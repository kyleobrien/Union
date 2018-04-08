# Union

Exploratory testing with [SBTM](http://www.satisfice.com/sbtm/) and [Markdown](https://daringfireball.net/projects/markdown/). More info about the format is available on the [GitHub repository](https://github.com/kyleobrien/Union).

## Features

A tiny extension that provides snippets to make your exploratory testing more pleasant. You get:

-   explore: a skeleton SBTM document.
-   bug: bold text that signifies you found something bad.
-   issue: italicized text that means you need to follow up on something later.

![All three snippets in action.](/images/snippet_demo.gif)

## Requirements

Since Markdown text suggestions are turned off by default, you might need to edit your settings if you want the snippets to work:

1.  Go into your Settings. User, Workspace, or Folder; your choice.
1.  Add the following JSON:

    ```
    "[markdown]": {
            "editor.quickSuggestions": true,
            "editor.wordBasedSuggestions": false
    }
    ```

## Release Notes

### 1.0.0

Initial release of Union!
