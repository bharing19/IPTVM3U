this method is for direct play

In a .txt file change extension to  .strm file ,  personaly i use notepad++ 

#KODIPROP:inputstreamaddon=inputstream.adaptive call to plugin
#KODIPROP:inputstream.adaptive.manifest_type=mpd  may vary  hsl also supported
#KODIPROP:inputstream.adaptive.license_type=com.widevine.alpha  Type of Licence may change depending services
#KODIPROP:inputstream.adaptive.stream_headers=User-Agent= Optional or could be required to make the stream work
#KODIPROP:inputstream.adaptive.stream_headers=Referer=  Optional or could be required to make the stream work
#KODIPROP:inputstream.adaptive.license_key= <Your Key Here> Or URL To Key query (https://Server/?deviceId=xxxx)
https:// xxxxx .mpd  .m3u8


where they to put strm file

https://github.com/Sphinxroot/IPTVM3U/blob/master/StreamFiles%20In%20Kodi/Path.txt


you can use in a folder named as the channel , it can be managed in many form , depending  on how you want them sorted

file naming must be the same  if you want to use a image as thumb   .jpg or .png  change extension to .tbn

exemple:
/userdata/playlist/video/CNN/ or /userdata/playlist/video/USA/News/CNN/
in the folder 
CNN.strm
CNN.tbn

then in kodi they will be show in the left panel in video at playlist , if not shown , in playlist  on the left panel   go in option ->  update library ..  so everytime you add another .. you don`t need to restart kodi
