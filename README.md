# Privacy-Police---Castle-Quest

**Effective date:** June 8, 2026

Castle Quest ("the extension") is a browser game in which you collect treasure
chests that appear as you browse and spend the coins building an isometric
castle. This policy explains what data the extension handles and how.

**Short version: Castle Quest does not collect, transmit, or sell any personal
data. All game data stays on your device.**

## What data the extension stores

The extension saves only your game state, locally on your device, using the
browser's `chrome.storage.local` API:

- **Coins** — your in-game coin balance.
- **Grid and roads** — the buildings and roads you have placed.
- **Game flags** — small bookkeeping values such as whether a treasure chest is
  currently active, which tab it is on, coins earned while the popup was closed,
  and whether you have seen the welcome tutorial.

This data exists only so the game can remember your progress between sessions.
It never leaves your browser.

## What the extension does NOT do

- It does **not** collect personal or identifying information (no name, email,
  account, or login).
- It does **not** read, store, or transmit the content of the web pages you
  visit, your browsing history, form inputs, passwords, or cookies.
- It does **not** send any data to us or to any third party — there are no
  external servers, analytics, tracking, or advertising.
- It does **not** sell or share any data, because none is collected.

## Permissions and why they are needed

- **`storage`** — to save your game progress locally (see above).
- **Host access (`http://*/*`, `https://*/*`) and the content script** — to
  display a clickable treasure chest overlay on the page you are viewing. The
  content script only checks that the page is a normal web page and adds the
  chest graphic; it does not read page content.
- **`tabs`** — to track which tab a chest appeared on so the chest indicator can
  be cleared when that tab is closed or navigated away.
- **`activeTab` / `scripting`** — to place a chest on the current page on demand.

These permissions are used solely to run the game. They are not used to monitor
your browsing.

## Data retention and deletion

Because all data is stored locally, you are in full control of it. You can erase
it at any time by removing the extension or clearing its storage from your
browser's extension settings. Uninstalling the extension deletes its stored
game data.

## Children's privacy

The extension does not knowingly collect any personal information from anyone,
including children.

## Changes to this policy

If this policy changes, the updated version will be published at the same
location with a new effective date.

## Contact

Questions about this policy can be sent to: **datasten77@gmail.com**
