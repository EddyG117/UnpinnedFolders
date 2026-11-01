# Unpinned Folders

Lets you use tab groups in Zen's normal (unpinned) tabs section, styled to look exactly like Zen's own folders. Zen folders for pinned tabs keep working as before.

## Setup

1. Open Zen's settings, go to **Zen Mods**, and click the settings button on this mod.
2. Turn on **Enable tab groups**.
3. Restart Zen.
4. Right-click a normal tab and choose **Add Tab to New Group**.

## Using groups

- Click a group's name to collapse or expand it.
- When a group is collapsed while you're on one of its tabs, that tab stays visible and the folder shows three dots.
- The dot on the folder icon and the bar beside a group's tabs show the color you picked for the group.

## Known issues

These come from how Zen handles Firefox's tab groups, and a styling mod can't fix them:

- Right-clicking a group's name doesn't open a group menu, so a group can't be renamed, recolored, ungrouped or deleted after it's created. To take tabs out, right-click a tab and choose **Remove from Group**. A group disappears when its last tab leaves.
- After restarting Zen, collapsed groups reopen expanded.
- After restarting Zen, and when you split two tabs that are already in a group, split views end up outside the group.
- Dropping a tab onto a group's name doesn't add it. Drop it between the group's tabs instead.
- Dragging a whole group into the pinned section pins its tabs one by one instead of moving the group.
- Zen's **Clear** button closes expanded groups (undo brings them back) but skips collapsed ones.
- Groups are named in Firefox's pop-up panel instead of inline in the sidebar, and can't have a custom folder icon.
