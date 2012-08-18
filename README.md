This is a hacky script to display notify-osd messages from grive.

I don't know how robust it is and it's quite a hack job.

Grive is created by Nestal Wan and is found at https://github.com/Grive/grive/

Once Google finally releases a Linux client for Google Drive, this script will
hopefully be obsolete.

It's intended to be called via a user's crontab like so:
*/2  *  *  *  *  sh /home/myself/bin/grive-sync.sh
(for every 2 minutes)

Install grive first an initialize a directory, then
you must edit the script first and change the appropriate variables.
