---
layout: page
title: Known Issues
permalink: /known-issues/
---

1. Some tabs are ignored.  For example, tabs with a URL of beginning with `file://` will not be removed.

1. The idle timer restarts any time Safari is closed.  For this reason, a long idle time of `Days` is unlikely to happen if Safari is restarted.

1. This tool has no special awarness of pinned tabs.  Pinned tabs will be treated like normal tabs.

1. Different windows are not handled specially.  If you have Minimum Tabs set to 2 and have two windows with two tabs, the two oldest tabs will be removed. 

1. On initial installation of CloseTabs, the menubar button may not work and restarting Safari may be required to get it working.

1. Closetabs processing sometimes quits closing tabs.  Enabling debugging causes it to start again.
