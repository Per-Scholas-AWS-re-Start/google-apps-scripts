# google-apps-scripts

# purge-old-emails

A [Google Apps Script](https://developers.google.com/apps-script/) script to automatically delete unarchived mail after 7 days that hasn't been starred or marked as important

## Quick Start

 1. Backup your emails using [Google Takeout](https://takeout.google.com/).
 2. Load this script into a new Google Apps Script [project](https://script.google.com/).
 3. Execute the _setPurgeTrigger()_ function to set a trigger that will call the _purge()_ function every day.
 
 A detailed blog post with more information can be found at [https://benbjurstrom.com/purge-email](https://benbjurstrom.com/purge-email)

## Acknowledgements

Thanks to [this gist](https://gist.github.com/jamesramsay/9298cf3f4ac584a3dc05) by jamesramsay for getting me started in the right direction.
