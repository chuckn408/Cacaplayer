The goal is to merge mpv and libcaca into a low-intensity video-player module for web-based implementations.
Normally, one would use "mpv libcaca somevideo.mp4". The goal is to have options or stand-alone player functionality.

Project site: derlg.ddns.net

Options:
-Drupal Module
  +(D7)[Video_Module]+[FFMPEG]+Custom_FFMPEG_Config
  +(D8)[FFMPEG_WRAPPER]+[Video_Upload]+{Custom_Config]
-Embedded VLC player
  + !--VLC already provides (nearly-hidden)files for embedding- just need to configure/compile--! +
-Embedded MPV player
  + Journey starts here https://github.com/mpv-player/mpv/issues/598
