---
layout: "post"
title: "I made my own link shortener"
---

Shortlinks are awesome, but to rely on a third party is to give up convenience, privacy and control.<!--more--> Back in the early 2010's I discovered `goo.gl`, the now discontinued Google URL shortener, and used it everyday. To save characters on a tweet, reddit post and to track clicks to personal projects of mine.

My social presence on the Net has [changed a lot within recent years][1], thanks to the Cambridge Analytica incident I became more privacy minded. This meant giving up tons of services, the Google URL shortener was one amongst them. On March 30, 2018 Google posted on their blog that `goo.gl` will be shut down, the shortener site was updated with the following message:

[1]: https://alex-esc.github.io/posts/follow-the-blog-on-mastodon.html

> *On March 30, 2018, we turned down support for goo.gl URL shortener. From April 13, 2018, only existing users were able to create short links on the goo.gl console. Analytics data was available for up to one year, until March 30, 2019, when goo.gl was discontinued. Previously created links will continue to redirect to their intended destination. Please see this [blog post][2] for more details.*

[2]: https://developers.googleblog.com/2018/03/transitioning-google-url-shortener.html

On their explanatory post they argued for dynamic links and against *URL's*, for some time now Google has been trying to monopolize cyberspace. First they came for search (once the old *do no evil* motto was dropped), then for email, social, cloud storage, typesetting software and now they want to disrupt URL's as a whole. Their plan is to replace search result links with Google's own version of the URL.

URL stands for Uniform Resource Locator, and in 1999's *[Weaving The Web][3]*, the Inventor of the Web himself *Tim Berners-Lee* explains his vision for the World Wide Web. Technically a URL is a type of URI (Uniform Resource Identifier), the purpose of URI's - and therefore the point of URL's - is to serve as an address analogous to a street map. The first page to be up on Tim's Web was `info.cern.ch`, this link perfectly captures Tim's vision for Web addresses, you would have a base domain, a sub domain and if needed some kind of sub document separated by a slash. Berners-Lee developed the web at European Organization for Nuclear Research, or C.E.R.N. for short, and because the server was already available for internal use at `cern.ch` the URI would naturally become `info.cern.ch`. The beauty of URL's was their ability to link together ideas and spaces. On *Team Human* ([2019][3.5]) author Douglas Rushkoff describes weblinks as a new tool for expression, just like on the Renaissance we got the the sonnet, today we got a new type of metaphor, we got hypertext: *"[Hypertext] allows anything to become a metaphor for anything else"* (Team Human, Chapter 80). The common word for URL is a link, this is the hidden elegance of weblinks, we intuitively understand the power of URL's to connect and link together two objects, those being spaces or ideas. It's so simple yet so elegant, one address as a door to an object.

> Book reveiws for both *Weaving the Web* and *Team Human* are in the works. Check the [post archive][4] for the reviews when available, or [subscribe to this blog][5] to get notified when the reviews are published.

The whole point of links is to represent; that's whats a web-page is, it's present, it's here, and it's represented by an address. Dead links are not a reflection of a broken system, but a sign of the organic elements of digital, tech evolves, grows and even dies, just like organisms do. A 404 error reflects the livelihood of the Net just as much as a live site. On the other side of the ring, against the organic Web, we have the synthetic Internet. A gray place were pages are [only present as long as someone is looking][3.6] at them *a la* [Schrödinger's cat][3.7]. This is the hell-world of dynamic websites, if you've ever tried to click on a link and an advertisement suddenly took it's place forcing you to click on the ad, you can thank dynamic websites for that.

[3]: https://en.wikipedia.org/wiki/Weaving_the_Web
[3.5]: https://rushkoff.com/books/team-human-book/
[3.6]: https://varia.zone/en/what-a-website-can-be.html
[3.7]: https://en.wikipedia.org/wiki/Schr%C3%B6dinger's_cat
[4]: https://alex-esc.github.io/posts/archive.html
[5]: https://alex-esc.github.io/posts/subscribe.html

Dynamic links are the antithesis of the organic Web, always on, always rendering, never incrementally changing like organism going through evolution, but updating in quantized seconds, like a digital clock jumping from minute to minute against the organic adventure that is the minute hand slowly drifting and making it's way around an analog clock. The organic Web is present, here while it last, while the dynamic Web is eternal, here to haunt you forever. Google's plan to kill the URL is to push web developers and independent creators to forget their old style websites and port them to a Google approved mobile optimized webapp. On an [April interview with Chrome's engineering manager][6] on WIRED magazine, the manager argued that URL's are just too complex for users. Hackers could fish innocent people, get their banking info, steal their identities, install malware, yuck! The solution? To surrender our turf and let Google distribute, maintain, own and rule the URL by surrendering verification to your majesty.


[6]: https://www.wired.com/story/google-wants-to-kill-the-url/

Killing their URL shortener was a sign of their aggression towards our spaces, *if the link was no more, what's the use for shortlinks? You may as well give it all up and deliver to the all powerful tax-man*. Some people - whom have already surrendered their opinions, thoughts and autonomy to various tech platforms - agreed with Google's master plan for a dummies Internet. But we're not dummies, we're people, we should build the people's Net, not a scaled corporate intra-net where a company owns and controls the means of digital creation, but a true democratic opening of the people and the products of our work and play.

The end of Google's URL shortener not only cut off some websites, but their people too. Tech savvy people like me use shortlinks all the time, but the more privacy minded ones like myself have come to advise against them. They track users n' clicks, sure they do provide with convenience for the author, but at the cost of the end user's privacy.

This is why I decided to make my own URL shortener, my site would not track users, be completely [transparent][6.5] and easy for every person tangled between both ends of the link. My little experience blogging has taught me *jekyll*, a software to create static websites like this one. Though simple HTML tricks and some tags and listings of *jekyll* posts I was able to hack together a simple interface to create shortlinks of my own. The first step I took to create my own URL abbreviator was to make a base website with the basic functionalities for a regular website. I made this baseline website by copying my blog post site and adding some users for quick configuration. I called this website base `post-clone`, since it's a clone of my post site. The idea behind it is to provide with some easily configurable basic features for a website, basic stuff like adding a website name, author, feed, description, contact links, about the author section, archive section, comment / feedback section and content license; you can configure all this features from one single file.

[6.5]: https://github.com/alex-esc/url

This would simplify setting up any future projects of mine, instead of starting from scratch every time I can just make a copy of `post-clone` and fill in the content and make some small changes. And so I did, I cloned it, configured it and added permalink functionality to enable the short links. Now if I want to create a short link I can just make a new post on my *url* site, where I host my shortlinks, and title the post, add the fill link and a short version. The end result would be a link like this `alex-esc.github.io/url/aboutme`. Remember that the last part of the url can be any combination of numbers and characters in true short link fashion.

In addition to creating shorter URL's, my site can also store links in a box of some kind. The idea is that I often find interesting pages, articles, comments or posts on the Net, and want to share them or save them for later. With my link box functionality I can do exactly that. This is especially exciting fro me because on [a previous post][1] I had narrated my excitement of discovering an obscure website and getting trapped on a hypertext wormhole, so by storing all the cool stuff I found online my site would be able to recreate this feeling to a future reader.

If you want to see the stuff that catches my eye on the Net, check out my linkbox at *[alex-esc.github.io/url/linkbox][7]*.

[7]: https://alex-esc.github.io/url/linkbox

And that's why I created my own URL shortener, what I think of URL's as a whole and what's this new linkbox about. With my own tools I come a step closer to digital autonomy. Also cuz it's fun to make websites and write long posts like this one.