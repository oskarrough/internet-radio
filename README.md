Here's the idea:

You have a folder with audio files and would like people to be able to listen through them in a synchronized, continuous and looped stream.

You have one endpoint, be it example.com or example.com/playlist.m3u. Once a user connects, playback will start and it will be synchronized/live amongst clients.

First approach is to define a point in time. From there you compare with current time. With that value, you should be able to calculate where and at which track the stream should start playback.
