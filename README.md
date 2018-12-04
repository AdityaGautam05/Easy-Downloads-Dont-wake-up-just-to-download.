# Easy-Downloads-Dont-wake-up-just-to-download.
This Project is for the ones who just wake up to start the downloads as it doesn't automatic download (at least for free). So what my script does it that, once you edit them with the wifi you use and add them in the windows task scheduler. It automatic connects you to the wifi at the desired time and starts your download. 


Let's first open the First file that is, connecttowifi.BAT

When you edit the file you get a script as
"netsh wlan connect ssid="lenovo" name=lenovo"
Since my wifi name was lenovo the ssid and the name has been configured according to my use.You need to open your CMD as administrative access to use the NETSH command for the first time.


netsh wlan show profiles
use the above command to get your network's wifi profile, and edit the connecttowifi file according to your usage.


Then get to the second file and replace the second line by the complete address of your torrent downloader.

And the end save both the files and add them to the windows task schedular.
At the time you want the scripts to run, it'll run without any problem.



(Note: You must not stop your download before quiting the torrent client, just quit it, so that the next time the script runs it downloads it)

*It was made for my college friend, as he loves downloading things.
