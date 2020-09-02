# Perfect Home - Themes

This is the place where you can find (and contribute your own) themes for the [Perfect Home](https://addons.mozilla.org/en-US/firefox/addon/perfect-home) firefox addon.

## What is a Theme?
It's basically a folder in this repo, containing one of these (or both):
- Thumbnails for websites - any number and any website.
- Custom CSS - that one can just copy & paste in settings and it will change the look & feel of the Perfect Home page.


## How to use a Theme?

### Directly from the extension settings
- Just open the extension settings (clicking the cog icon in the top-right corner)
- Make sure to enable "Themes from github" in the "Privacy" section
- In "Customize" section - select a theme you want.
- ... more details to follow...


### Manually
- For custom CSS it's easy - just copy the css code and paste it in the Extension's settings "Custom CSS" field.
- For thumbnails images - whatever works best for you:
  - You can download this repo (or just a theme folder) and replace thumbnails for your bookmarks from there (thumbnails are cached in the extension, so you can even delete the folder afterwards). This is the preferred method, as it doesn't require internet to load your homepage (all images are cached).
  - You can click on an image and copy a link to it and paste as a custom thumbnail (remember to copy the Raw image url, not the github page's one). This will be a bit slower (depending on your connection), as the page needs to load the remote images.



## Contribution rules

### Naming conventions
There are a couple of restrictions to the theme and file names:
- Folder name (obviously, as it's a folder) must be unique. If you wish, you can add namespace like so: `tom123-mytheme`.
- A nice screenshot of either the *Perfect Home* page or just the thumbnails (e.g. from a graphical app) with a name: `_screenshot.png`. This will be used as a preview on the future themes site.
- `README.md` file inside the theme folder should contain:
  - A good description in markdown format.
  - Some nice screenshots.
  - Author's contact details (email/github username), so when something doesn't work, people know who to ask.
- For future updates and contributions it would be good to include a template/file from the graphical application you've used (e.g. Sketch, Figma, Powerpoint), with a specific name e.g. `_template.extension` (e.g. `_template.sketch`).
- General rule is that files with `_` in front of the name will not be considered as icons, otherwise all PNG files inside the theme folder will be considered as such.

You can have a look at the sample themes that are already in the repo.
Once we have a decent number of themes, there's a plan to create some sort of a gallery website :smile:.
