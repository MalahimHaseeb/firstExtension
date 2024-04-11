# Attractive Extension

This is the main file for creating an attractive extension.

## Manifest

The `manifest.json` file contains the metadata and configuration for the extension.

```json
{
    "manifest_version": 3,
    "name": "Attractive Extension",
    "version": "1.0",
    "description": "Check how to create extensions",
    "action" : {
        "default_popup" : "index.html"
    }
}
```
### Explanation of manifest.json

- `manifest_version`: Specifies the version of the manifest file. This field indicates which version of the manifest specification the file conforms to. For example, `"manifest_version": 3` indicates that the manifest file adheres to version 3 of the specification.

- `name`: The name of the extension. This is the display name of your extension as it will appear in the browser's extension manager and marketplace.

- `version`: The version of the extension. This field indicates the version number of your extension. It helps users and developers keep track of updates and changes.

- `description`: A brief description of the extension. This field provides a short summary of what your extension does. It helps users understand the purpose and functionality of your extension.

- `action`: Specifies the action to be taken when the extension icon is clicked. This field defines the behavior of your extension's icon in the browser's toolbar or menu.

  - `default_popup`: Specifies the HTML file to be opened as a popup when the extension icon is clicked. This field points to the HTML file that contains the content to be displayed in the popup window when the user clicks on the extension icon.


Feel free to copy and paste this content into your README file!
