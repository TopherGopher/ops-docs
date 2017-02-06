## Create a WordPress Archive
1. In order to do this process, it is required that the site be entirely completed.
  a. This includes prototype 3 corrections, QA corrections, and anything that came up in training 
2. Complete the WordPress Go Live Process
3. Navigate to Jenkins 
  * Run the update job on production (eg. production-1fee > Build with Parameters > Update)
  * Once the update is done, run the backup job on production (eg. production-1fee > Build with Parameters > Backup)
4. Create a link in the DRUD file tool and send to client
  * Do not set the limit above 48 hours
  * Run the following for an expiration of 48 hours, replacing example with the file location (ex: autismspi/production-autismspi-1485918804.tar.gz)
    * nmd file url example -e 48
