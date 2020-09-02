# Pure white
White icons without the background. Ideal for a dark site.

![Screenshot](_screenshot.png)


# Custom CSS
```css
header { height: 0; }
header .title {display: none; }
.bookmarks.no-labels .item-folder .item-thumb { mask-size: 110px; }
.bookmarks.no-labels .item-folder .item-title {
  font-size: 18px;
  max-width: 94px;
  margin-bottom: 6px;
}
.bookmarks .item {
  filter: none;
  opacity: 0.8;
  transition: opacity .3s ease-out, transform .2s;
}
.bookmarks .item:hover { opacity: 1; transform: scale(1.05); }
```

# Template
[sketch file](_template.sketch)
