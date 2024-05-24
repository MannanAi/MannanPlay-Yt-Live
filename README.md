Many public broadcasts are now available on YouTube as live videos. I was looking for a way to add these to my Android TV as digital channels. As a result, I created this service to get the live feed of a YouTube video as an HLS or M3U streaming link. I then add it as a channel to any IPTV client. If you are interested, [here is a GitHub repository](https://github.com/MannanAi/MannanPlay-Yt-Live/blob/main/channels.csv) with a list of channels available on YouTube.

# Youtube IPTV Channels
It creates a permanent link for a Youtube live channel or video, which adds it to any IPTV client.

## For a Youtube Channel
It picks up the live feed of a YouTube channel. It works well when a YouTube channel has a single live feed or goes live frequently. It does not work when a channel has multiple live feeds simultaneously. Please use the video link for this case. 

```bash
# format of the link
https://mannanplay-yt-live.mayilgamingmd.workers.dev/stream/$youtube_channel_id/master.m3u8

like
# example
https://mannanplay-yt-live.mayilgamingmd.workers.dev/stream/UCYlh4lH762HvHt6mmiecyWQ/master.m3u8
```

## For a Youtube Video
It picks up the live feed of a YouTube video. The video should be live for it to work.

```bash
# format of the link
https://mannanplay-yt-live.mayilgamingmd.workers.dev/video/$youtube_video_id/master.m3u8

# example
https://mannanplay-yt-live.mayilgamingmd.workers.dev/video/Nq2wYlWFucg/master.m3u8```

# Support
Please include a link to this GitHub repository if you use this service.
