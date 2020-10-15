---
layout: "post"
title: "How and why I read e-books"
---

### This one's new for me

Writing about tech had often involved watching YouTube tutorials and condensing their content into this blog, or at least it used to.<!--more--> Now that I try to tackle more nuanced ideas like [digital rights][1], [Internet culture][2] and to an extent [politics online][3], I can no longer find my kick in ten minute videos.


[link](###My-e-book-setup)

[1]: https://alex-esc.github.io/posts/what-tech-says-about-us.html
[2]: https://alex-esc.github.io/posts/alt-tech.html
[3]: https://alex-esc.github.io/posts/dont-quit-social-media-fix-social-media.html

I wear [my inspiration][4] with pride, but my idols weren't always the same. Four years ago I got into podcasts, long and polished discussions about tech drew me in but in the beginning I only listened to [Relay FM's Cortex podcast][5]. For years I was starving for long form content so I decided to listen to talks about whatever topic on a regular basis. Until I discovered Google's talk [YouTube page][6] I found my go to thinker: [Douglas Rushkoff][7].

[4]: https://alex-esc.github.io/posts/im-on-medium.html
[5]: https://www.relay.fm/cortex
[6]: https://invidio.us/user/AtGoogleTalks
[7]: https://en.wikipedia.org/wiki/Douglas_Rushkoff

Rushkoff is a media theorist who coined the term viral media, and by extension viral video, this is why he tends to be misinterpreted as a marketing guru when in fact he is as anti-marketing as you can get. Douglas's work focuses on digital media environments, and how they affect society and the economy; On his [2017 talk at Google][8] he spoke about his most recent book at the time: *Throwing Rocks at the Google Bus*. The talk spoke to me, it seems like every little tangent and sentence unveiled some hidden truth behind the tech curtain, from his casual chit-chat with the audience at the beginning to his profound economical analysis of the digital environment he had me hooked. Only a day later, by pure change, [he went on TED][9] to lecture about his new book *Team Human*.

I was blown away, it seemed Doug could do no wrong. Shocked by his presentation I searched for his YouTube channel, there I found an [interview with Bo Burnham][10], one of my favorite comedians, the video description pointed to [his podcast][11], so I rushed to add the RSS feed into my phone's podcast app. I listened to Doug's podcast for months, I burned through his hole catalog. On one of his latest episodes he said he's going on a small break and that the break should work as reflection time for both himself and his listeners. As any author would do, he winked to the idea that now's the perfect time to read his newest book; He got me hook, line, and sinker.

[8]: https://invidio.us/watch?v=0EnmH95016w
[9]: https://invidio.us/watch?v=Is1YUQVYkvY
[10]: https://invidio.us/watch?v=TkUt_KG0zAc
[11]: https://teamhuman.fm/

The book is eye opening, it condenses so much vital information to interpret today's media landscape, from evolutionary biology to media bias to agriculture and then back to digital technologies. There truly is no other book or media work like *Team Human*, but after reading it I still craved for more! By listening to Rushkoff and reading online discussions about technology the names Tristan Harris and Jaron Lanier always came about, so I decided to gave them a try.

This had lead me to my first official book phase! Looking into those new authors has lead me to more cool people and ideas, but a problem quickly arrived: How am I going to download, format, organize and read those books?

### My e-book setup

To end on a high note, and to please the tech-heads like myself, here's how my setup looks like:

Get the book, preferably on EPUB format, then add it to my digital library on my computer, use a software called Calibre to edit the book's meta-data and add a nice cover, send it to my Android phone - my reading device of choice - via Syncthing and read it with KOReader. If the file doesn't play well with my reader of choice, then I can always count with MuPDF as a last resort, since it's a simple universal document viewer.

Now a more in depth tour of my setup:


| e-book format    | book manager       | sync them with my phone or e-reader                              | read them on my phone or e-reader               |
|:-----------------|:-------------------|:-----------------------------------------------------------------|:------------------------------------------------|
| PDF, EPUB or OPF | Calibre on desktop | Syncthing or the cloud for desktop-mobile, usb sync for e-reader | KOReader on Android or Kindle, MuPDF on Android |


#### Calibre

This is my e-book manager of choice, there's truly northing as good like it on desktop. Think of it as iTunes but for e-books, you have a library of books that you can organize, tag, read and modify. Some useful features include editing meta-data, meaning if a PDF is missing it's cover Calibre can look it up for you and modify the file so it has the correct cover.

Calibre allows me to rename all my book files in just the way I like, add the best looking covers, transform from one book format to another, organize my books inside the app and on the file system and to export all books into one drive, in this case into my phone.

Calibre is free of charge and licensed under the GNU General Public License, created and maintained by [Kovid Goyal](https://kovidgoyal.net/). You can support Calibre's development and other projects from it's creator [by becoming his Patreon](https://www.patreon.com/kovidgoyal).

* [Download Calibre](https://calibre-ebook.com/)

#### Syncthing

Syncthing is like your own cloud storage, instead of using iCloud or Google Drive to send your e-books from one device to another (or any file for that matter) you can use this nifty program to sync one folder on, let's say, your Desktop to your Android device.

To sync your e-books with your Android phone, first create a folder on your desktop with all your e-books, note that this can be accomplished with calibre, then point syncthing to it and set up the syncthing app on your Android. It will create a new folder on your phone that perfectly mirrors the folder you told it to, your e-book's folder. Now whenever you download a new book on your desktop or mobile device syncthing will make sure both devices stay updated with the same books and files.

[Jakob Borg](https://twitter.com/jakobborg) is the head programmer behind Syncthing, his work and effort keeps the software free of charge. You can [contribute to the code](https://github.com/syncthing/syncthing) or [donate directly to the project if you scroll down on his website](https://syncthing.net/). This software is licensed under the Mozilla Public License 2.0.

* [Download Syncthing](https://syncthing.net/)



#### KOReader

KOReader is a super nice piece of software, its a document viewer for e-readers and android. KOReader can browse local files, open e-books, keep track of your progress, highlight text, add notes, lookup words on the dictionary or Wikipedia, translate words, it has both light and dark mode and it's beautifully minimalistic.

It's free, zero, nada. It's libre, open, GNU (Affero GPL v3.0). It runs on Android (The dark theme on a OLED screen looks gorgeous) and e-reader devices such as kindle. KOReader is maintained by e-book-loving volunteers, there's no donation information available on their website, so to show them your support [join their forum](https://www.mobileread.com/forums/forumdisplay.php?f=276) or thank the [top contributors](https://github.com/koreader/koreader#contributors) directly.

* [Download KOReader for Android](https://f-droid.org/en/packages/org.koreader.launcher/)
* [Installation instructions for Kindle devices](https://github.com/koreader/koreader/wiki/Installation-on-Kindle-devices)


#### MuPDF

MuPDF is an extremely minimalist, bloat free, PDF & e-book reader. It lacks many features that KOReader has like a robust file browser and dark mode, but it's beauty it's in it's simplicity: It opens PDF's quickly and plainly. If a particular book's format doesn't play well with KOReader, this hasn't happened to me, or if you just want to open a book or article quickly without adding it to your book collection or dealing with a robust system, then MuPDF works best.

This project is economically maintained by [Artifex Software](https://artifex.com/), originally published by Tor Andersson in 2005. This PDF reader is free software licensed for personal use under the GNU Affero General Public License. You can modify MuPDf by forking the [original repository](http://git.ghostscript.com/?p=mupdf.git;a=summary).

* [Download MuPDF for Android, Linux, Mac or PC](https://mupdf.com/)


### More book stuff to come

Right now I'm almost done with Douglas Rushkoff's *Team Human* and I have a lot to say about it; You can expect a review in the near future. Doug is not my only source for wisdom, many other authors and books are on my list, I think a book club of sorts will unfurl on this blog.

Once the *Team Human* review is done, I will continue to dive deeper into digital technologies, if you want my individual take on tech you can check out my [other posts](https://alex-esc.github.io/posts/archive.html) or [my tech medium page](https://medium.com/digital-rights).