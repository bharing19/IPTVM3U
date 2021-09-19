# IPTVM3U


Hybrid list adapted for kodi using different addons to make the stream work

all list work with the Playlistloader addon  for kodi 18.9 or 19+ matrix as exception of Streamlink Tester  since some dependencies are not ported to python 3 yet


################


# Youtube : Video Id :  No API required : link Update required (UPD)
#EXTINF:-1 tvg-logo="" group-title="", (YT) (v_id) (UPD)
https://www.youtube.com/watch?v=

# Youtube : Channel ID : API required : No Update required
#EXTINF:-1 tvg-logo="" group-title="", (YT) (c_id)
plugin://plugin.video.youtube/play/?channel_id=IDHERE&live=1


################


# Twitch : Channel Name
#EXTINF:-1 tvg-logo="" group-title="", (TWITCH) (C_N)
plugin://plugin.video.twitch/?mode=play&channel_name=

# Twitch : Channel ID
#EXTINF:-1 tvg-logo="" group-title="", (TWITCH) (C_id)
plugin://plugin.video.twitch/?channel_id=IDHERE&amp;mode=play


################


# Streamlink Tester
#EXTINF:-1 tvg-logo="" group-title="",  (SLT)
plugin://plugin.video.streamlink-tester/?action=play&url=


################


# Send To Kodi
#EXTINF:-1 tvg-logo="" group-title="", (STK)
plugin://plugin.video.sendtokodi/?


################


# Dailymotion : VLC Only
#EXTINF:-1 tvg-logo="" group-title="", (For VLC)
https://www.dailymotion.com/video/IDHERE#tab_embed.m3u8

# Dailymotion : LIVE Only
#EXTINF:-1 tvg-logo="" group-title="", (DM)
plugin://plugin.video.dailymotion_com/?url=IDHERE&amp;mode=playLiveVideo

# Dailymotion : VOD Only
#EXTINF:-1 tvg-logo="" group-title="", (DM_VOD)
plugin://plugin.video.dailymotion_com/?mode=playVideo&url=IDHERE


################



