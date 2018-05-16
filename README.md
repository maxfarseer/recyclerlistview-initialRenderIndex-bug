# Example of recyclerlistview bug

### How to reproduce:

1.  Generate small list of elements (here in repo 3 items)
2.  Open the browser window with enough heigh to display all items
3.  Set up any initialRenderIndex (0,1,2)

### Expected results:

All items displayed.

### Actual results:

No one element rendered

### Screenshots

https://monosnap.com/file/rLQjgBXDla3I67yYVIHNOWX0LCZAND - normal page, height not enough
https://monosnap.com/file/IooCvMWVxPyaHgm5ouTOSMadNYV1KP - blank page, when height is enough
