# Test Matrix

Command: `atom.workspace.getActiveTextEditor().getPath()`

* `real-dir/test.md`
    * Open from tree-view: `/Users/Lee/Source/test-atom-9879/real-dir/test.md`
    * Open from fuzzy-finder: `/Users/Lee/Source/test-atom-9879/real-dir/test.md`
    * Open from <kbd>Cmd+O</kbd>: `/Users/Lee/Source/test-atom-9879/real-dir/test.md`
    * Open via drag-and-drop: `/Users/Lee/Source/test-atom-9879/real-dir/test.md` (New window appears)
* `fake-dir/test.md`
    * Open from tree-view: `/Users/Lee/Source/test-atom-9879/real-dir/test.md`
    * Open from fuzzy-finder: **Does not show up in list**
    * Open from <kbd>Cmd+O</kbd>: `/Users/Lee/Source/test-atom-9879/real-dir/test.md`
    * Open from drag-and-drop: `/Users/Lee/Source/test-atom-9879/real-dir/test.md` (New window appears)
