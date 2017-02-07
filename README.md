# Scripts

### sync_git
A script that finds all git repositories from the current directory and does a `git pull` to sync all the repositories. If any errors are found, the script wil let you know which ones failed. 

### git_dev_cron
This script utilizes the sync_git script and it used to setup a cron job to sync the repositories every hour in the background. It also uses terminal-notifier which will use a MacOS notification to let you know when the script starts/stops. 
