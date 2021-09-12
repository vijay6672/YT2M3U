
<h1 align="center"> YT2M3U </h1>

[![M3U generator for YouTube](https://github.com/vijay6672/YT2M3U/actions/workflows/m3u_Generator.yml/badge.svg)](https://github.com/vijay6672/YT2M3U/actions/workflows/m3u_Generator.yml)

`https://raw.githubusercontent.com/vijay6672/YT2M3U/main/youtube.m3u`
Not all the channels telecast live all the times.
If any channel have multiple live streams only 1st live stream will be visible.
Updated m3u links of YouTube live channels, auto-updated every 3 hours.


### Add more channels
Edit `youtube_channel_info.txt` to add your favourite YouTube livestreams

Create a pull request

### Usage
Paste this URL: `https://raw.githubusercontent.com/vijay6672/YT2M3U/main/youtube.m3u` to any player which supports M3U playlists

### Run the tool on your local machine
``` bash
git clone https://github.com/vijay6672/YT2M3U.git
cd YT2M3U
chmod +x autorun.sh
./autorun.sh
```

Do not forget to add a cron job set for every 4 hours(or 5) if you plan to run the script locally.
