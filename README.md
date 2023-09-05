# supermemo_anti_merge
When you are editing HTML, press `Ctrl + Shift + Alt + M` to make the HTML in supermemo unique. This is done by adding a current time string at the end of the text.

You can make the time string invisible by adding the following to your `bin/supermemo.css`:

```
.anti-merge {
  position: absolute;
  left: -9999px;
  top: -9999px;
}
```

On why SuperMemo merges HTML text, see [how registry works in SuperMemo](https://supermemopedia.com/wiki/Registry). But, simply put, SuperMemo has the same registry entry for texts, as long as the texts are identical. And the one registry entry has the one HTML file. So they merge.
