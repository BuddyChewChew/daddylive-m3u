-------------------------------------------------------------------------------------------
2/2/25 - **This repo no longer works. The repo it was forked from is gone along with the user. If anyone has the files to make it work and wants to share.
Drop a link in the comments**
-------------------------------------------------------------------------------------------

**Important:** Due to TinyURL’s use of Cloudflare, the playlist short links have been updated from TinyURL to Bit.ly. The old TinyURL links will continue to work once the protective mode is lifted, but it's recommended to switch to the new Bit.ly links.

# DaddyLive Live TV & Sports Playlists

DaddyLive is a platform that offers free live TV and sports streaming across selected categories. Users can stream and watch live TV directly through their browser without the need for an account or subscription.

For added flexibility, this repository provides an M3U playlist featuring DaddyLive's channels. With this, you can load the streams into any IPTV application that supports M3U-formatted playlists.

You can view the full list of channels provided by DaddyLive [here](https://href.li/?https://dlhd.so/24-7-channels.php). 

**Note:** Adult channels have been excluded from the main playlist. If you wish to include these channels, the playlists can be found [here](https://github.com/dtankdempse/daddylive-m3u/tree/main/adult).

## Playlist Formats:

- **playlist.m3u8:**
  A standard M3U playlist. If you're using this playlist, make sure your IPTV application allows the setting of a custom `Referer` and `User-Agent` header. The headers must be set in order to access the streams. Failure to set the required headers will result in a 403 error when attempting to stream.
  
  **Playlist:** `https://bit.ly/ddy-m3u1`  
  **EPG URL:** `https://bit.ly/ddy-epg1`  
  **Referer:** `https://lewblivehdplay.ru/`    
  **User-Agent:** `Mozilla/5.0 (iPhone; CPU iPhone OS 17_6_0 like Mac OS X) AppleWebKit/605.2.10 (KHTML, like Gecko) Version/17.6.0 Mobile/16F152 Safari/605.2`     

- **tivimate_playlist.m3u8:**
  This playlist is specifically formatted for use with TiviMate. To use it, simply load the URL provided in this repository into Tivimate as an "M3U Playlist." No additional setup is needed as Tivimate handles the required headers for playback.
  
   **Playlist:** `https://bit.ly/ddy-m3u2`  
   **EPG URL:** `https://bit.ly/ddy-epg1`  
   **Referer:** `Included`  
   **User-Agent:** `Included` 

- **kodi_playlist.m3u8:**
	This playlist is designed for Kodi, utilizing `#KODIPROP` properties to handle the necessary stream settings, including the required headers. It is optimized for Kodi's PVR IPTV Simple Client, ensuring compatibility with your Kodi setup. This format is primarily designed for Kodi, but it may or may not be compatible with other applications.
	
   **Playlist:** `https://bit.ly/ddy-m3u3`  
   **EPG URL:** `https://bit.ly/ddy-epg1`  
   **Referer:** `Included`  
   **User-Agent:** `Included` 

- **vlc_playlist.m3u8:**
  Optimized for VLC Media Player. This playlist uses VLC-specific formatting to ensure streams play correctly, including setting the necessary headers via `#EXTVLCOPT`. This format is primarily designed for VLC, but it may or may not be compatible with other applications.
  
   **Playlist:** `https://bit.ly/ddy-m3u4`  
   **EPG URL:** `https://bit.ly/ddy-epg1`  
   **Referer:** `Included`  
   **User-Agent:** `Included`

If none of these playlists work with your IPTV application, you can try using the [m3u-playlist-proxy](https://github.com/dtankdempse/m3u-playlist-proxy). This proxy acts as a middle layer to help resolve potential issues with playing the playlists, especially if your IPTV app doesn't support setting the required headers.

## Usage Instructions:

1. Choose the playlist format that suits your application or media player.
2. Add the playlist URL to your IPTV application.
3. Ensure that your application supports the required settings, such as setting the required headers for streams to play.

## Disclaimer:

This repository has no control over the streams, links, or the legality of the content provided by dlhd.so (including all mirror sites). It is the end user's responsibility to ensure the legal use of these streams, and we strongly recommend verifying that the content complies with the laws and regulations of your country before use.

