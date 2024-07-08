# slack-archive

Website view of old SPAAM slack workspace (public channels only).

Note this does not have an integrated search functionality.
You will have to use <kdb>ctrl</kbd> + <kbd>f</kbd> search functionality in your browser.

## Generation

The static website was generated using @hfran 's `[slack-export-viewer](200~https://github.com/hfaran/slack-export-viewer)`.

0. Change into this repository
1. Export the slack archive Zip from the Slack export interface (and rename file so use underscores not spaces)
2. Install the tool with

    ```bash
    pip install slack-export-viewer
    ```
3. Generate the static `html` 

    ```bash
    slack-export-viewer -z SPAAM_Slack_export_Oct_28_2019_-_Jul_8_2024.zip --html-only -o ./
    ```
