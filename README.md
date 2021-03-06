# ghost-md-imgur
**Upgrades imgur images to embeds.**

Works in posts and pages.

## Usage
Use a standard markdown image tag with the URI set to a standard imgur path with
no file extension.

**Example**
```
![Now I know why construction is taking so long](https://imgur.com/gallery/WE8El)
```

## Installation

1. Copy/clone this repo into {yourGhostInstall}/content/apps
2. Use your favorite package manager to install dependencies. I.E. `npm install`
3. Edit the "active_apps" record in the settings table of your database to
include "ghost-hbs-imgur". I.E. `["ghost-md-imgur","other-app"...]`
4. Restart Ghost.

**Note:** active_apps might be listed as activeApps depending on your version.

## References
https://github.com/TryGhost/Ghost/wiki/Apps-Getting-Started-for-Ghost-Devs
