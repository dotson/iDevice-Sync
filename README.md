iDevice Sync
=============
*An Alfred workflow for syncing each of your iDevices individually.*

A simple workflow that allows you to sync your iDevices by name. The workflow is triggered by the keyword **"sync"**.

Upon actioning, the workflow displays all iDevices that you have listed by name in the variable list for the workflow. Actioning any of the iDevices in the list will tell Finder to look for them in a new window and start the sync. If a named device is not listed, Alfred will try a few times to find it and then throw an eeor if not found.

**Known Issues:**

This is based purely on GUI scripting which is easy to break if Apple changes even the smallest thing. Since Catalina, there's no other known way to do this via applescript.