## clone_Slackware_repo_lftp
Clone Slackware mirror to a local folder using lftp

#### Default mirror : ftp://ftp.osuosl.org/.2/slackware

#### Use:
```sh
$ ./clone_Slackware_repo_lftp_JBs.sh
```

#### You can chose:
* the **Slackware version** (e.g., **14.1**, **14.2**, **current**)
* the architecture (**32** or **64** bits)
* with **sorce code** or not
* with **md5 checksum** or not

#### Also can create a ISO file with:

```sh
$ ./create_ISO_without_some_packages_JBs.sh
```
You can create the ISO with all packages or remove all the packages in **packagesList** from the final ISO
