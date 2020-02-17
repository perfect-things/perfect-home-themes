# Perfect Home - Themes

This is the place where you can find (and contribute your own) themes for the [Perfect Home](https://addons.mozilla.org/en-US/firefox/addon/perfect-home) firefox addon.

## What is a Theme?
It's basically a folder in this repo, containing one of these (or both):
- Thumbnails for websites - any number and any website.
- Custom CSS - that one can just copy & paste in settings and it will change the look & feel of the Perfect Home page.

## How to use a Theme?
- For custom CSS it's easy - just copy the css code and paste it in the Extension's settings "Custom CSS" field.
- For thumbnails images - whatever works best for you:
  - You can download this repo (or just a theme folder) and replace thumbnails for your bookmarks from there (thumbnails are cached in the extension, so you can even delete the folder afterwards). This is the preferred method, as it doesn't require internet to load your homepage (all images are cached).
  - You can click on an image and copy a link to it and paste as a custom thumbnail (remember to copy the Raw image url, not the github page's one). This will be a bit slower (depending on your connection), as the page needs to load the remote images.

## Contribution rules
In addition to the above, a Theme should also have:
- Unique name (obviously, as it's a folder). If you wish, you can add namespace in a format: `tom123-mytheme` or even nest themes (if you plan to add more than one), so we have `tom123/mytheme`
- A nice screenshot of either the *Perfect Home* page or just the thumbnails (e.g. from a graphical app).
- A good description (e.g. `README.md` file) ideally with that screenshot.
- Author's contact details (email/github username), so when something doesn't work, people know who to ask.
- For future updates and contribution - you can include a template/file from the graphical application you've used (e.g. Sketch, Figma, Powerpoint)

You can have a look at the sample themes that are already in the repo.
Once we have a decent number, I will think about some gallery website :smile:.


The ultimate plan is to hook this repo to the extension, so you can just select a theme directly from there!
