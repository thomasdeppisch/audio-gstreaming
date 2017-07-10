# Multichannel audio streaming with Gstreamer1.0
Here you can find some example pipelines I used for streaming multichannel Vorbis encoded audio streams.
By using a defined config interval the rtp headers are sent every couple of seconds and therefore starting and stopping streams (senders and receivers) is possible anytime.
Jack Audio Connection Kit was used as streaming source and sink.
