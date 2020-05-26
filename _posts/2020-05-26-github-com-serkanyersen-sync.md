---
title: sync
categories: ['typescript', 'sftp', 'nodejs']
---
## [sync](https://github.com/serkanyersen/sync)

### syncs your local folder with remote folder using scp

 - **Username**: your username that you use to connect to remote machine
 - **Auth method**:
    - **Password in config**: This the least secure version of auth. It will keep your password in the config file **as plain text** do not use this please
    - **Ask during connect**: This option will ask your password again every time you start `syncjs` your password will not be stored anywhere.
    - **Private Key**: Most secure option, just provide the path for your key file and syncjs will do the rest

 - **Hostname or IP of the server**: Tell syncjs where to connect
 - **Port to connect**: defaults to `22` this usually is what you want
 - **Local path**: syncjs will automatically detect this as the root of your project, but if you only want to sync one specific folder, **provide it here as full path**
 - **Remote path**: This is where copy of your local folder lives in the remote server. Make sure you type full path here as well.


License
-------
MIT

