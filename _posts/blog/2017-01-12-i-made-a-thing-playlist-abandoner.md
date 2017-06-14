---
title: "I Made a Thing: Playlist Abandoner"
layout: post
---

It's been a while since I had to update the [Projects page][projects], but it
finally happened for the first time since _October 2015_.

I've written a tiny browser extension for Safari and Chrome called
[Playlist Abandoner][github]. It does absolutely nothing until you go to a
playlist page on YouTube (youtube.com/playlist?list=xyz). On a playlist page,
it adds a little button next to each video in the list. That button opens the
watch page for the video.

![Playlist Abandoner Screenshot][screenshot]

"But wait," you say, "doesn't clicking the video _already_ open the video's
watch page?!". Well, yes, but there's one key difference: when you click on a
video in a playlist, it opens the video in the context of the playlist, which
means that when the video ends, the next one will start playing automatically.

Playlist Abandoner opens the watch page from _outside_ the context of the
playlist, meaning that you'll watch that one video and nothing else. Well,
unless you click on another video manually, of course.

I mainly built this extension for myself; I make heavy use of the "Watch Later"
system on YouTube, and most of the time I only want to watch one video from that
list at a time. With Playlist Abandoner, I just click the magic new button and
I'm taken to that video, by itself, and when it ends, it just… ends.

I'm sure there's a very small market for this extension, because the main point
of YouTube playlists is to be able to watch them all in one go. But if it sounds
like something you want, it's available to install from the [Chrome webstore][chrome].

For Safari, it's a little more complicated; to create an actual `.safariextz`
file, you have to be a member of the Apple Developer Program, which costs $99 per
year. Seeing as I don't (yet) have any iOS apps to publish in the App Store, I
don't really want to throw away $99 a year to publish a free Safari extension.
To install the extension in Safari, you'll need to follow the instructions
[here][github].

[projects]: http://joshasch.com/projects
[github]: https://github.com/jobbogamer/PlaylistAbandoner
[chrome]: https://chrome.google.com/webstore/detail/playlist-abandoner/bofdplnnckbbkffmkpmndfljedbldafo
[screenshot]: /images/2017/01/12/playlist-abandoner.png