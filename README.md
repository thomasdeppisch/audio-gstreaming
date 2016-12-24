# Examples for streaming audio with Gstreamer1.0
Here you can find some example pipelines I used for streaming Vorbis encoded (stereo) rtp audio streams via multicast ip addresses. You can achieve multichannel streaming by starting several pipelines.
By using a defined config interval the rtp headers are sent every couple of seconds and therefore starting and stopping streams (senders and receivers) is possible anytime.
