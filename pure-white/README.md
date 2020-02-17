# Pure white
White icons without the background. Ideal for a dark site.

![Screenshot](_screenshot.png)


# Custom CSS
```css
header { height: 0; }
header .title {display: none; }
.bookmarks .item-bookmark .item-title { display: none; }
.bookmarks .item-folder .item-thumb {
  background: center url("https://raw.githubusercontent.com/perfect-things/perfect-home-themes/master/pure-white/folder-outline.png") no-repeat;
  background-size: auto;
  background-size: 110px;
}
.bookmarks .item-folder .item-title {
  margin-top: -56px;
  font-size: 18px;
  color: #fff;
  z-index: 9;
  position: relative;
  font-weight: 200;
  letter-spacing: 1.5px;
}
.bookmarks .item {
  filter: none;
  opacity: 0.6;
  transition: opacity .3s ease-out, transform .2s;
}
.bookmarks .item:hover {
  opacity: 1;
  transform: scale(1.05);
}
```

# Template
[sketch file](_template.sketch)
