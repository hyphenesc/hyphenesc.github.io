---
layout: "post"
title: "Understanding podcast RSS feeds."
---

After some toying around with RSS I think I've got it kind of figured out<!--more-->, so yeah expect a full tutorial in the future, for now here is a brief explanation of my setup.

## What do I want from my podcast?

* The podcast basics: title, author, description, etc.
* A free way to host the audio without time limits or file size limits.
* An itunes ready podcast feed.
* Easily upload new episodes.
* Automatically generating feed, no manual XML coding necessary.
* The option to create, edit and host the XML feed at your terms.

## How to get there.

Youtube playlist + podsync + Feedburner

These tools will help you get your podcast up and ruining for free, here we go:

### Step one, upload to a YouTube playlist.

Uploading new episodes and editing previous ones is super simple, you need to create a YouTube playlist, you can add your videos to it and use the YouTube tools to add a thumbnail, edit name and description and so on.

Because YouTube is free you can pretty much use it as a file hosting service.



### Step two, transform the playlist into a podcast feed.

The next step is to create an RSS feed for the YouTube playlist and make it itunes podcast compatible, so here you have two options, you can make your podcast feed automatic or manual.

#### Manual or automatic?

* **Automatic:** An automatic feed is the easiest option, *if you go automatic you only need to upload your videos into YouTube, add them to your podcast playlist and your podcast will be automatically distributed to itunes or spotify once you set it up*. There are a few downsides, if podsync or Feedburner go out of business or stop working your podcast will not get into itunes or spotify, downside two: Because we're using YouTube to host the podcast **all your podcast episodes will be video only**, not such a big deal because you can make the video a still image but your audience will use more data listening to your podcast, you could still use a YouTube playlist to upload your podcast and get an audio only podcast feed but for that you need to use the manual method.
* **Manual:** Not as difficult as it sounds, but by writing your own XML you have full control over your podcast feed, you can use certain tools to do the heavy lifting for you, and you can still use YouTube playlists to host your files and even transform your video playlist into an audio only podcast feed (those methods will be covered in the next tutorial, subscribe to this blog for future updates).

### Step tree, setting up your automatic podcast feed.

Copy the URL link of your YouTube playlist, for example:

	https://invidio.us/playlist?list=PLmyix0xax7AbCKEjhdekE2RknCHQYLPmU

Now go to https://podsync.net/ and paste your link inside the box that says 'paste your link here'

You will get a new URL, copy that one and go to http://feedburner.google.com/.

Follow the instructions in there, add the link you just copied from podsync in the blox below 'Burn a feed right this instant. Type your blog or feed address here'

And there you go, your feed should now be done and ready for itunes or spotify podcasts, to view your feed click on the little grey RSS icon besides the name of your feed, it will look something like this:

	https://feeds.feedburner.com/Jet_so_plusVideoEditing
	
Done! You can use your newly created feedburner link to submit your podcast feed to your favorite podcast app.


### Advanced features:

More features like transforming this video podcast YouTube Feed into an audio only podcast feed and transferring your feed to other host services or even hosting it on your own will be covered on the full in depth tutorial.

The full tutorial will be out sometime soon, so subscribe to this blog and keep an eye on more tips, blog and general goofyness.