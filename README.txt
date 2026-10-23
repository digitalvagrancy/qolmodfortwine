QoL MOD FOR TWINE  v1.2.0   (for Twine 2.12.1)
October 2026. An unofficial, unsupported modified build of Twine, created
with Claude.
Not affiliated with or endorsed by the Interactive Fiction Technology
Foundation (IFTF) or the Twine project. Twine is a registered trademark of
IFTF. Use at your own risk, and back up your story library first.
Provided as is. No support is offered and bug reports are not accepted.

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
  story map. A passage with several coloured tags has its outline divided
  evenly between them (halves, thirds, and so on). Needs Twine >
  Preferences > Show Passage Tags As > Color. To go back to Twine's original
  thin stripe, untick "Show tag colors as outlines" in the same place.
- Right-click tags: right-click a passage in the story map to tick/untick
  existing tags. Right-click one of several selected passages to change all
  of them. It can't create new tags; do that in a passage editor.
- Double-click to create: double-click empty space in the story map to create
  a new passage there and open it for editing.
- Quick Paste: a Quick Paste button in passage editors inserts your saved
  text at the text cursor (replacing any selected text).
  Setup: Twine (Modified) > Preferences > Quick Paste text, type or paste
  your snippet.
  Use: click in the passage text where you want it, then click Quick Paste.
  The button is greyed out until a snippet is saved, and needs
  "Use Enhanced Editors" ticked (the default). One snippet slot.

OTHER CHANGES
- The app is labelled "Twine (Modified)" in the menu bar, and the About
  windows show the Twine version first, then a few details about this mod.
- Check for Updates now warns first that installing an official update will
  remove the mod.
- The "Report a Bug" button was removed, so problems with this build don't
  go to the Twine project.

INSTALL
1. Close Twine.
2. Right-click your Twine shortcut > Open file location, then open the
   "resources" folder.
3. Rename "app.asar" to "app.asar.original".
4. Copy the new "app.asar" from this repository into that same folder.
5. Relaunch. The menu bar should now say "Twine (Modified)".

UNINSTALL
1. Close Twine.
2. In the same "resources" folder, delete the new "app.asar".
3. Rename "app.asar.original" back to "app.asar".

NOTES
- Your stories and settings are stored elsewhere and are not touched.
- A Twine update or reinstall will overwrite the mod.
- This app.asar is built for Twine 2.12.1 only. Don't copy it over any other
  version.
- Please don't report problems with this build to the Twine project.

LICENCE AND SOURCE
Twine is free software under the GNU GPL v3 (https://github.com/klembot/twinejs).
This mod is a modified version of Twine 2.12.1 and is shared under the same
licence (see LICENSE). The full list of code changes is in
source-changes.patch; the original source is at the link above.

VERSION HISTORY
v1.2.0  Labelled "Twine (Modified)" in the menu bar; new About windows;
        warning before Check for Updates.
v1.1.0  Renamed to QoL Mod for Twine. Tag outlines split evenly between
        multiple tags, with an option to restore the original stripe.
        Double-click to create a passage. Report a Bug button removed.
v1.0.0  Pinned passages, tag outlines, right-click tag menu, Quick Paste.
