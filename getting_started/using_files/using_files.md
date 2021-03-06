## Using Files

Turbo.net let you use files located on your device or on popular online storage providers such as OneDrive and Dropbox.

### Local File System

Users may access files on their local system when launching an application in the Cloud or on a local container instance.

#### Access local files with Run in Cloud (Turbo.net for PC)

You can access files on your device when an application is launched using a Turbo.net native client. On the Portal, this mode is referred to as **Run in Cloud (Windowed)**:

![](/docs/getting_started/using_files/accessing-files-from-local-system-via-run-in-cloud-windowed-1.png)

Applications running in this mode will show files from the local device as **Home on My PC** or **Home on My Mac** in the File Open and Save dialogs.

![](/docs/getting_started/using_files/accessing-files-from-local-system-via-run-in-cloud-windowed-2.png)

Files from the local system may also be accessed using the `\\\\tsclient\\\{drive\}` remote path.

![](/docs/getting_started/using_files/accessing-files-from-local-system-via-run-in-cloud-windowed-2-bg.png)

#### Access local files with Run On My PC (Turbo.net for PC)

Users who run Turbo applications on their local Windows Desktop may access the local file system directly. Open the Settings dialog from Turbo Launcher and check the **Access to local user folders** setting.

![](/docs/getting_started/using_files/local-user-folder-access.png)

User folders such as Desktop, Downloads, Documents, Music, Pictures, and Videos are now accessible in the Turbo application that are launched on the machine. Non-system drives are also directly accessible. 

#### Access local file system files with Turbo.net for Mac

Users may access files from their local system when they launch an application in the cloud and stream it to their device via Turbo for Mac.

![](/docs/getting_started/using_files/mac-powerbi.png)

Applications running in this mode will show files from the local system under the **Home on My Mac** mapped drive in the File Open and Save dialogs.

![](/docs/getting_started/using_files/mac-power-bi-home-on-my-mac.png)

Files from the local system may also be accessed using the \\\\TSCLIENT\\Home remote path.

![](/docs/getting_started/using_files/mac-net-use.png)

### Cloud Storage Services

Connecting a cloud storage service, such as OneDrive or Dropbox, to your applications on Turbo.net is a seamless way to access your files quickly.

From your Portal, click on **Files** to access the storage services for your account.

Then, click on the **Connect** button to link the storage service to your account, allowing Turbo applications to load and save data to the storage service.

![](/docs/getting_started/using_files/connecting-a-storage-service-onedrive-to-your-account-1.png)

You will be asked to authenticate your account with the storage service to link it with your applications.

![](/docs/getting_started/using_files/db-connect-onedrive-2.png)

When the authentication succeeds, the storage service status will show as connected and give you the option to Disconnect.

![](/docs/getting_started/using_files/connecting-a-storage-service-onedrive-to-your-account-3.png)

Files from the storage service will be available under the **T:\\** drive for applications running in the cloud.

![](/docs/getting_started/using_files/connecting-a-storage-service-onedrive-to-your-account-4.png)
