iDevice Sync v1.2
=============
*An Alfred 2 workflow for syncing each of your iDevices individually.*

A simple workflow that allows you to sync your iDevices by name. The workflow is triggered by the keyword **"sync"**.

*I highly recommend downloading this from Packal as they provide an updating feature for future versions of the workflow.
http://www.packal.org/workflow/idevice-sync*

Upon actioning, the workflow searches for all connected iDevices and lists them by name in an Alfred window. Actioning any of the iDevices in the list will tell iTunes to begin syncing the chosen iDevice. A notification is returned via the default notification system when the sync is complete.

Using the *'alt'* modifier key when selecting a device from the list will force the workflow to sync all devices listed.

**Known Issues:**

The method used for triggering the completion notification is a little hack-y and may be unreliable in some sync attempts. This will be improved as becomes possible based on the scripting ability of iTunes improving (unlikely).

**Changelog:**
- **v1.2** New Icon (modified from here:http://www.alessioatzeni.com/metrize-icons/); Fixed the broken start/complete messaging.
- **v1.11** Even more improved notification reliability, hopefully.
- **v1.1** Added 'sync all devices' option. Improved completion notification reliability.
- **v1.0** Initial Release
