# youtube-dl-and-BASH-Linux

the reason this bash script was created is because youtube-dl, while downloading long-sized videos, fails and thus stops downloading the video or videos when you least expect it. the error is as follows (I have tried with various versions and it has the same problem):
ERROR: unable to download video data: HTTP Error 403: Forbidden.

the goal therefore is to prevent youtube-dl from failing. So I created a script that retries the download so that it fails. I also added a logic that allows you to insert the link of the playlist to download ... it's still immature, maybe one day I'll fix it when I have time.

I publish two scripts, the first called BASH1 only has the logic to retry the download. The second, BASH2, also has the logic to insert the link, but as mentioned above, it needs to be fixed.

of course you have to install youtube-dl before using the script.

have fun and I recommend what you download!
