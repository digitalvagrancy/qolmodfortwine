TWINE QoL MOD  v1.0.0   (for Twine 2.12.1)
October 2026. An unofficial, unsupported Twine mod created with Claude.
Not affiliated with or endorsed by the Twine project. Use at your own risk,
and back up your story library first.

WORKS WITH
- Twine 2.12.1 desktop app only (this replaces the whole app file).
- Designed for Windows. Mac/Linux is untested: it is the same file, but it
  lives in a different folder.
- Any story format (Chapbook, Harlowe, SugarCube, etc). The features are part
  of Twine's editor, not the story format. Tested with Chapbook only.
- Not for the browser version of Twine.

NEW FEATURES
- Pin: a Pin button in passage editors moves a passage into its own column to
  the left of the editing panel, so reference passages stay open while you
  write. Close a pinned panel with its X. Pins are forgotten when you close
  the story or Twine.
- Tag outlines: tag colours show as a coloured outline around passages in the
  story map (one ring per coloured tag). Needs Twine > Preferences >
  Show Passage Tags As > Color.
- Right-click tags: right-click a passage in the story map to tick/untick
  existing tags. Right-click one of several selected passages to change all
  of them. It can't create new tags; do that in a passage editor.
- Quick Paste: a Quick Paste button in passage editors inserts your saved
  text at the text cursor (replacing any selected text).
  Setup: Twine > Preferences > Quick Paste text, type or paste your snippet.
  Use: click in the passage text where you want it, then click Quick Paste.
  The button is greyed out until a snippet is saved, and needs
  "Use Enhanced Editors" ticked (the default). One snippet slot.

INSTALL
1. Close Twine.
2. Right-click your Twine shortcut > Open file location, then open the
   "resources" folder.
3. Rename "app.asar" to "app.asar.original".
4. Copy the new "app.asar" from this zip into that same folder.
5. Relaunch.

UNINSTALL
1. Close Twine.
2. In the same "resources" folder, delete the new "app.asar".
3. Rename "app.asar.original" back to "app.asar".

NOTES
- Your stories and settings are stored elsewhere and are not touched.
- A Twine update or reinstall will overwrite the mod.

LICENCE AND SOURCE
Twine is free software under the GNU GPL v3 (https://github.com/klembot/twinejs).
This mod is a modified version of Twine 2.12.1 and is shared under the same
licence (see LICENSE.txt). The full list of code changes is in
source-changes.patch; the original source is at the link above.

VERSION HISTORY
v1.0.0  Pinned passages, tag outlines, right-click tag menu, Quick Paste.
