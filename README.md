# Twitch Chat Video

Fetch chat for a Twitch broadcast and create a video replay.

This program makes use of [Accord's .NET FFMPEG Library](http://accord-framework.net/index.html) for video rendering.

## Usage

Enter the URL of a video and then click make video. It should look like this: `https://www.twitch.tv/videos/<Video ID>`. You may also simply use the Video ID.

The preview window provides an example of what your render will look like. Double click the preview image for a true to size preview!

## Options 

### Background Color
The background color to use for the video.

### Chat Color
The color to use for chat messages. Note that usernames and bits will always be drawn with the appropriate color.

### Font
The font to use for chat messages. Any font installed onto your system is available.

### Font Size
The font size to use for chat messages.

### Video Width
The horiztonal resolution of resulting video.

### Video Height
The vertical resolution of resulting video.

### Line Spacing
Inserts additional padding between chats by different users.

### Badges
Enable or disable user chat badges.

### Vod Chat
If enabled, chat posted by users during a vod will be included.

## What settings should I use?

Twitch Chat Video ships with some reasonable defaults, but choose what works for you. While you have the option to render large videos, it's probably not what you're looking for. Here are some good guidelines:

* Keep your video resolution and font size small.
* 15 FPS is more than sufficient for anything except non-stop chat.
* If you have the time to wait, VP8 is going to produce better results than MPEG4.

## Help!

If something doesn't seem to be working properly, you have something you'd like to see added, or you simply know way more about all of this than me and have some feedback, feel free to [create an issue](https://github.com/cairface/TwitchChatVideo/issues)!
