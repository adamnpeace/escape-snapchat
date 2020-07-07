# Escape Snapchat

If you go to [accounts.snapchat.com/accounts/downloadmydata](https://accounts.snapchat.com/accounts/downloadmydata), you get the option to "download your data" but most of the data you'd want to keep is in the form of memories.

If you want to export your memories, you'd have to download them manually, one by one.

This Python script saves you the trouble.

Just follow the steps below and you'll have all your memories, with relevant timestamps and _modification date_.

_This script requires Python 3 which can be [installed like so](https://opensource.com/article/19/5/python-3-default-mac)._

- Copy `json/memories_history.json` file from inside the archive you download from the above link and paste it into the repo folder.
- Then, run `python memories-downloader.py`
- That's it! Bear in mind, the time the script takes depends on the number of memories you have saved.

## Privacy

There's no telemetry or internet connectivity outside of actually gathering the download URLs from Snapchat servers and then downloading the files from AWS.
