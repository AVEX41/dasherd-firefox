# Dasherd Firefox

> Replaces new tab with a custom dashboard, in Firefox

## How to use
1. Install npm dependencies:
   ```bash
   npm install
   ```
2. Build the extension:
   ```bash
   npm run build
   ```
3. Load the extension in Firefox:
   - Open Firefox and navigate to `about:debugging#/runtime/this-firefox`
   - Click on "Load Temporary Add-on..."
   - Select the `manifest.json` file from the `dist` directory
4. Open a new tab to see the custom dashboard in action.
5. To make changes, edit the source files in the `src` directory and rebuild the extension using `npm run build`.

## Features
- [x] Application open on new tab
- [ ] Input needed packages
- [ ] Create a generalized UI
- [ ] Search bar
- [ ] Search bar with interchangeable search engines
- [ ] Bookmark groups:
    - [ ] State persistence
    - [ ] Edit page:
        - [ ] Add bookmark group
        - [ ] Remove bookmark group
        - [ ] Add bookmarks to bookmark group
        - [ ] Remove bookmarks from bookmark group
- [ ] Bookmark widgets, can choose between different groups
- [ ] Bookmark widget with search
- [ ] Bookmarks with automatic icon fetching
- [ ] Bookmark widget with custom icon