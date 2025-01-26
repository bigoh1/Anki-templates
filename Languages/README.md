# How to live preview changes

```bash
less-watch-compiler ./Languages/src ./Languages/dist --main-file Styling.less
live-server ./Languages/preview
```

# Note != card

Keep in mind that `/Languages/` represent a _Note_ type, not a _card_ type.  
That is, one set of fields (in a _note_) generates two _cards_ automatically.
