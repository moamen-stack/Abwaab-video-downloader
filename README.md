# Abwaab-video-downloader
A simple .bat file that uses yt-dlp and ffmpeg to download any abwaab video (Windows only for now)
Here is how you can download a video from awbaab with this tool: (feel free to DM me or create an issue and i will give you the tutorial with screenshots or video recordings)
First, extract the .zip file, inside of it, there are the following files, yt-dlp.exe, ffmpeg.exe, ffplay.exe, and ffprobe.exe
Open a CMD in that extracted folder, simply, double click the abwaab_video_downloader.bat file
A new CMD window will open asking you for the following:
1. name of the video, for example, "lesson 1"
2. the abwaab video URL, simply copy the link of the abwaab video from the URL bar and paste it there
3. now the .m3u8 playlist URL, this is how you do it:
Keep the video open, press F12 (fn+F12 on some laptops), developer tools will appear on the right, Now, if it isn't shown in the top of the developer tools, click on that double arrow and click on "networks", play the video you want to download for a second or two, there will be a filtering search bar, right there, type ".m3u8" and hit enter, at first, nothing will show up, simply hit "ctrl+R" to refresh the page, you will see that a few things start to pop up, the others are useless, all we need is playlist.m3u8, right click it, go to copy and hit "Copy URL", then go back to that terminal window and paste that long command and hit enter, the download will start, the time to download is around 2-5 minutes on my wifi, but it varies depending on your wifi speed and how long the video is, once it finished, check the folder where the .bat file exists, there will be a .mp4 file with that exact name you chose, you can then open it with a video player and play the video
This worked amazingly for me, but just note that it may not work well for everyone, dont fight me or flood my email with angry emails saying why it does not work
I am currently working on making it so that it no longer need a .m3u8 link, I will update the project and files if I was able to possible make it not need the .m3u8 link
And feel free to fork this repository and add your own changes to it and maybe even make it run on other operating systems yourself

Credits:
* **[yt-dlp](https://github.com)** - Used for fetching and downloading video streams. (Licensed under The Unlicense / GPLv3+)
* **[FFmpeg](https://ffmpeg.org)** - Used for merging, converting, and post-processing video/audio tracks. (Licensed under the GNU Lesser General Public License [LGPL v2.1](https://gnu.org))
