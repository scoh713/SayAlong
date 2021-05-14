# SayAlong
Language learning tool that play video for each subtitle line

**1. What is the SayAlong**

SayAlong is a web document that include codes written in JavaScript. It loads one of video files like YouTube Video, Movie, TV series with one of their subtitles, and play them in the unit of subtitle in the browser window. This tool makes it easy to learn languages or songs by listening and speaking along.

**2. How to use**

You can click on the 'Select File' button next to 'Video' to load a video file. Also you can click on the 'Select File' button next to 'Subtitle' to load the subtitle file for the video.
After loading a video and the subtitle for that, you can click on each subtitle line to play that part of the video. And you can change the playback speed by manipulating the 'Speed' slide bar from 0.5 to 1. 

![Cap 2021-05-10 16-27-47-914](https://user-images.githubusercontent.com/17871491/118210183-10d61080-b4a5-11eb-9192-427987508d95.jpg)

Alternatively, you can use the hot keys below:

- 'z': play previous subtitle line
- 'x': play current subtitle line
- 'c': play next subtitle line
- 's': one level lower the playback speed
- 'f': one level up the playback speed

**3. Running environment**

It works in the following environment:

- Web browser: Chrome
- Video format: mp4
- Subtitle format: srt

You can convert from any subtitle format to srt using http://convert.4get.kr/. Or you can also make your own subtitle or editing using "Subtitle Edit 3.6.0" that can be obtained in https://github.com/SubtitleEdit/subtitleedit/releases.
One thing to note is that you need to run the "SayAlong.htm" file in the directory containing the video and subtitle files. This is because the browser protects the directory for security reasons.
