# Remote Banner Extension

Add a remotely-hosted important message banner to a specific page.

## Development

### Local Install

```bash
git clone git@github.com:inderpreet99/remote-banner-extension.git
```

To load this extension in local Chrome browser, open up chrome://extensions/ in your browser and click “Developer mode” in the top right. Now click “Load unpacked” and select the extension’s directory. You should now see your extension in the list.

Go to https://bostonsikhsangat.com/hukamnama/ to see the background be `red` to indicate the extension is working.

### Making changes

When you change or add code in the extension, come back to chrome://extensions/ page and reload. Chrome will reload the extension.

## Todo

* [ ] Modify Hukamnama page to show a banner at the bottom.
* [ ] Use a remotely hosted banner. Example: Use `body` from https://jsonplaceholder.typicode.com/posts/1
* [ ] Allow configurable page actions to change the above API URL
* [ ] Allow configurable page actions to change the API URL's JSON path like `$.body`
