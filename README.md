# JQDE (jQuery Desktop Environment)
## [Try it out!](https://sevenworksdev.github.io/JQDE/example.html)
This JavaScript library allows you to create a "Desktop Environment" in your browser using one simple line of code.
![jqde](https://github.com/SevenworksDev/JQDE/assets/91027492/db4669a1-7ba8-4633-8b04-1cd94135e6af)

## Functions

### `jqde.create(name)`

Creates a JQDE environment.

**Parameters:**
- `name`: The name of the JQDE desktop.

### `jqde.background(color)`

Sets the background to the given color.

**Parameters:**
- `color`: The color to set as the background.

### `jqde.addApplication(icon, name, content)`

Adds an application to JQDE.

**Parameters:**
- `icon`: The path to the icon image.
- `name`: The name of the application.
- `content`: The HTML content to be displayed in the application.

### `jqde.removeApplication(name)`

Removes an application by its name.

**Parameters:**
- `name`: The name of the application to be removed.

### `jqde.exit(type)`

Performs an exit action based on the specified type:
- `0`: Refreshes the page.
- `1`: Goes back to the previous page in the browser history.
- `2`: Closes the browser tab.

**Parameters:**
- `type`: The exit type (0, 1, or 2).
