# Union

Exploratory testing with [SBTM](http://www.satisfice.com/sbtm/) and [Markdown](https://daringfireball.net/projects/markdown/) using a simple, formatted outline that prefers convention over new syntax. For more information, check out the [GitHub repository](https://github.com/kyleobrien/Union).

## Features

Three snippets to make your exploratory testing more pleasant. You get:

-   __explore__: a skeleton SBTM document.
-   __bug__: bold text that signifies you found something bad.
-   __issue__: italicized text that means you need to follow up on something later.

Here's a quick demo:

![All three snippets in action.](https://github.com/kyleobrien/Union/raw/master/union/images/snippet_demo.gif)

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
