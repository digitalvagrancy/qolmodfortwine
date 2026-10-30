QoL MOD FOR TWINE  v1.5.1   (for Twine 2.12.1)

October 2026. An unofficial, unsupported modified build of Twine, created
with Claude.

Not affiliated with or endorsed by the Interactive Fiction Technology
Foundation (IFTF) or the Twine project. Twine is a registered trademark of
IFTF. Use at your own risk, and back up your story library first.

Provided as is. No support is offered and bug reports are not accepted.
Please don't report problems with this build to the Twine project.

WORKS WITH
- Twine 2.12.1 desktop app only (this replaces the whole app file).
- Designed for Windows. Mac/Linux is untested: it is the same file, but it
  lives in a different folder.
- Any story format (Chapbook, Harlowe, SugarCube, etc). The features are part
  of Twine's editor, not the story format. Tested with Chapbook only.
- Not for the browser version of Twine.

INSTALL
1. Close Twine.
2. Right-click your Twine shortcut > Open file location, then open the
   "resources" folder.
3. Rename "app.asar" to "app.asar.original".
4. Copy the new "app.asar" into that same folder.
5. Relaunch.

NEW FEATURES: STORY MAP
- Tag outlines: tag colours show as a coloured outline around passages. A
  passage with several coloured tags has its outline divided evenly between
  them (halves, thirds, and so on). Choose Twine > Preferences > Show Passage
  Tags As > Outline (the default), Color Stripe (Twine's original thin line)
  or Name. If you were using Color, it switches to Outline once.
- Right-click a passage for a menu:
    Rename     A small box with the name selected. Links to the passage in
               other passages are updated, including Chapbook {link to} and
               {embed passage} inserts.
    Branch     Adds a link to the end of the passage and creates the new
               passage, named by continuing the number (Open1 becomes Open2).
               The link comes from the Link template preference.
    Connect    Click the first passage, choose Connect, then click a second
               passage. The first gets a link to the second. Esc cancels.
    Duplicate  A copy named "Name copy".
    Delete     Deletes straight away. Ctrl+Z undoes it.
    Tags       Tick or untick existing tags. The menu stays open so you can
               change several. If the passage is one of several selected, the
               change applies to all of them. New tags are made in the
               passage editor.
- Double-click empty space to create a passage there. It opens with the
  rename box ready. Esc keeps "Untitled Passage".
- Resize passages: hover the bottom-right corner of a passage and drag the
  circle. Minimum size is the normal small size, there is no maximum, and it
  snaps to the grid if Snap to Grid is on. Bigger passages show more text.
- Zoom: the zoom buttons are replaced by a percentage dropdown (30% to 100%,
  plus "Fit all passages"). Hold Ctrl and scroll to zoom smoothly around the
  mouse pointer. The - and = keys step 10%. Hold Alt and scroll to scroll
  sideways.
- Delete or Backspace with passages selected asks first. Enter confirms and
  Esc cancels.

NEW FEATURES: WINDOWS
- Pin: a Pin button in passage editors moves a passage into its own column to
  the left of the editing panel, so reference passages stay open while you
  write. Every pinned passage gets its own full-height column, side by side.
  Close a pinned passage with its X.
- Resizable: drag the left edge of any column (it highlights when you are in
  the right spot) to change its width. The editing panel's width is saved in
  Preferences > Dialog Width (shown as Custom). Each pinned column remembers
  its own width.
- Windows sit edge to edge, with no gaps.
- Remembered windows: when you reopen a story, the same pinned passages,
  editor, and Story Stylesheet, JavaScript, Details and Passage Tags windows
  come back, in the same order and sizes. This works after closing and
  reopening Twine. It is saved per story, so renaming a story's passages
  while a window is closed means that window won't come back.

NEW FEATURES: PASSAGE EDITOR
- Quick Paste: a Quick Paste button inserts your saved text at the text
  cursor (replacing any selected text).
  Setup: Twine (Modified) > Preferences > Quick Paste text, type or paste
  your snippet.
  Use: click in the passage text where you want it, then click Quick Paste.
  The button is greyed out until a snippet is saved, and needs
  "Use Enhanced Editors" ticked (the default). One snippet slot.
- Array: select lines of text, one entry per line, and click Array. An array
  like ['a', 'b', 'c'] is added on a new line below, and your lines are kept.
- Link template: Preferences > Link template sets the link Branch and
  Connect create. {passage} is replaced with the target name. The default is
  [[▹ Label.->{passage}]]

OTHER CHANGES
- The menu bar says "Twine (Modified)", and the About windows show the
  Twine version first, then a few details about this mod.
- Check for Updates now warns first that installing an official update will
  remove the mod.
- The "Report a Bug" button was removed, so problems with this build don't
  go to the Twine project.
- Dropdowns in Preferences are readable in dark mode (they could show white
  text on a white list).

UNINSTALL
1. Close Twine.
2. In the same "resources" folder, delete the new "app.asar".
3. Rename "app.asar.original" back to "app.asar".

NOTES
- Your stories and settings are stored elsewhere and are not touched.
- A Twine update or reinstall will overwrite the mod.
- This app.asar is built for Twine 2.12.1 only. Don't copy it over any other
  version.
- Stories saved with this mod open normally in stock Twine. The only changes
  to story files are the ones you make yourself (links, tags, passage sizes
  and zoom).

LICENCE AND SOURCE
Twine is free software under the GNU GPL v3 (https://github.com/klembot/twinejs).
This mod is a modified version of Twine 2.12.1 and is shared under the same
licence (see LICENSE.txt). The full list of code changes is in
source-changes.patch; the original source is at the link above.

VERSION HISTORY
v1.5.1  Windows are remembered after closing and reopening Twine. Cancel on
        the left and the action on the right in confirmation windows. The
        right-click tag menu stays open. Dark-mode dropdown fix.
v1.5.0  Pinned passages in side-by-side columns, resizable window widths,
        windows edge to edge, remembered windows. Delete key asks first.
        Outline is now a choice in Show Passage Tags As.
v1.4.0  Zoom dropdown and smooth Ctrl+scroll zoom. Resize passages by
        dragging a corner. Right-click Connect.
v1.3.0  Right-click Rename, Branch, Duplicate and Delete. Double-click to
        create then rename. Array button. Alt+scroll. Link template.
v1.2.0  Labelled "Twine (Modified)" in the menu bar; new About windows;
        warning before Check for Updates.
v1.1.0  Renamed to QoL Mod for Twine. Tag outlines split evenly between
        multiple tags. Double-click to create a passage. Report a Bug
        button removed.
v1.0.0  Pinned passages, tag outlines, right-click tag menu, Quick Paste.
