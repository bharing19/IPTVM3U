# IPTVM3U


Hybrid list adapted for kodi using different addons to make the stream work

all list work with the Playlistloader addon  for kodi 18.9 or 19+ matrix as exception of Streamlink Tester  since some dependencies are not ported to python 3 yet


################


# Youtube : Video Id :  No API required : link Update required (UPD)
#EXTINF:-1 tvg-logo="" group-title="", (YT) (v_id) (UPD)
plugin://plugin.video.youtube/play/?video_id=IDHERE

# Youtube : Channel ID : API required : No Update required
#EXTINF:-1 tvg-logo="" group-title="", (YT) (c_id)
plugin://plugin.video.youtube/play/?channel_id=IDHERE&live=1

If Multiple Live From The same Channel Change &live=2 ...and so on  need to be tested to fit the Channel Naming

################


# Twitch : Channel Name
#EXTINF:-1 tvg-logo="" group-title="", (TWITCH) (C_N)
plugin://plugin.video.twitch/?mode=play&channel_name=

# Twitch : Channel ID
#EXTINF:-1 tvg-logo="" group-title="", (TWITCH) (C_id)
plugin://plugin.video.twitch/?channel_id=IDHERE&amp;mode=play


################

** Token Retreivers **

# Streamlink Tester

#EXTINF:-1 tvg-logo="" group-title="",  (SLT)
plugin://plugin.video.streamlink-tester/?action=play&url=URLHERE

Usefull For many  Site That Use .php ending  EX: .php?id=IDHERE

- DASH .mpd Stream  No DMR + No Referrer
- IF DMR  use https://github.com/Sphinxroot/IPTVM3U/tree/master/StreamFiles%20In%20Kodi

https://streamlink.github.io/plugin_matrix.html

# Tested  WebSite :

https://piczel.tv/watch/CHANNELNAMEHERE

https://goodgame.ru/channel/CHANNELNAMEHERE

# Send To Kodi

#EXTINF:-1 tvg-logo="" group-title="", (STK)
plugin://plugin.video.sendtokodi/?URLHERE

# Tested  WebSite :

https://www.youtube.com/channel/IDHERE/live

https://www.youtube.com/watch?v=IDHERE

https://www.dailymotion.com/video/IDHERE

https://www.twitch.tv/CHANNELNAMEHERE

https://www.veoh.com/watch/IDHERE

https://vimeo.com/IDHERE

https://ok.ru/live/IDHERE|User-Agent=Mozilla/5.0 (Linux; Android 10) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/87.0.4280.101 Mobile Safari/537.36

https://dlive.tv/CHANNELNAMEHERE

https://livestream.com/accounts/IDHERE/events/IDHERE

https://picarto.tv/CHANNELNAMEHERE

################


# Dailymotion : LIVE Only
#EXTINF:-1 tvg-logo="" group-title="", (DM)
plugin://plugin.video.dailymotion_com/?url=IDHERE&amp;mode=playLiveVideo

# Dailymotion : VOD Only
#EXTINF:-1 tvg-logo="" group-title="", (DM_VOD)
plugin://plugin.video.dailymotion_com/?mode=playVideo&url=IDHERE

################

# Dailymotion : VLC Only
#EXTINF:-1 tvg-logo="" group-title="", (For VLC)
https://www.dailymotion.com/video/IDHERE#tab_embed.m3u8


################

HLS Stream URl can be tricked by using

|User-Agent=

|Referer=

|X-Forwarded-For=




