# file_sync
Synchronize local files w/ Google Drive using mklink /j

Use this method to synchronize any directory on Windows to your cloud backup service of choice. 
Configure this on multiple computers to synchronize across all machines.

Taken from a post on WoW forums (http://us.battle.net/forums/en/wow/topic/18300739344)

1) Install the cloud storage app of your choice.
2) *MOVE* the directory you wish to synchronize from it's original location to the cloud storage folder. The directory should no longer exist in it's original location.
3) In an admin command prompt, enter the following command:
  mklink /j "C:\your\local\directory" "C:\Users\<username>\<yourcloudfolder>\directory"
4) The directory is stored in the cloud storage folder, and linked to it's original location. This will make sure it's always backed up to the cloud storage.
