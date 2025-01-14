---
title: "The Ultimate Guide to Mining Sentences with YouTube"
date: 2024-01-13T18:48:49-06:00
summary: "My step by step guide on how to setup YouTube for the best mining experience."
draft: false
tags: ["Blog", "Language Learning", "Migaku", "Japanese"]
showAuthor: false
showHero: false
---



## Designate a YouTube account



You don't want to mix the YouTube account that you use for regular entertainment with the one you'll use for sentence mining; it just makes it harder to fully commit to one or the other. So, as a first step, I recommend that you assign or create a YouTube account with no previous activity for the sole purpose of consuming content on your target language. In general, after following these steps I also recommend taking the opportunity to clear YouTube as a source of distraction in your computer and using it for entertainment in the living room TV or somewhere else to make a strong mental connection between using the site on a pc and studying a language.  

## Unhook: Eliminate distractions

When browsing through YouTube, a lot of people get the feeling that they are just wasting their time watching videos that they aren't even interested in. It is normal to feel bad about this and start blaming your lack of discipline or self control, but you don't really notice all of the things that the site bombards you with to keep you in until you get rid of them. You'll be surprised how different the YouTube experience is without all of those intrusive distractions, with only your carefully selected subscriptions and the search bar to find videos that you actually want to watch.

{{< button href="https://chromewebstore.google.com/detail/unhook-remove-youtube-rec/khncfooichmfjbepaaaebmommgaepoid" target="_blank" >}}
Install Unhook
{{< /button >}}

Clicking on the extension icon will show you the pop-up menu. If it appears like this, you need to turn it on by clicking on the big gray button:

![Unhook Off](/images/youtube-guide/unhook-off.png)

These are my recommended settings, but you can adjust it to your liking:

![Unhook Config](/images/youtube-guide/unhook-config.png)

{{< alert >}}
__Warning!__ Enabling	 the settings marked with __red rectangles__ is __not recommended__ and interferes with the following extension's functionality.
{{< /alert >}}

## PocketTube: Better video browsing

### Subscription Manager

{{< button href="https://chromewebstore.google.com/detail/pockettube-youtube-subscr/kdmnjgijlmjgmimahnillepgcgeemffb" target="_blank" >}}
Install PocketTube Subscriptions Manager
{{< /button >}}

### Playlist Manager

{{< button href="https://chromewebstore.google.com/detail/pockettube-youtube-playli/bplnofkhjdphoihfkfcddikgmecfehdd?hl=en" target="_blank" >}}
Install PocketTube Playlist Manager
{{< /button >}}

## uBlockOrigin: Ads and extra elements blocking

Almost everyone knows that adblockers block, well... ads, but not a lot of people know that some of them can also block specific elements in a page. The one that I prefer is uBlockOrigin; it has that function and we're going to eliminate distracting clutter.

{{< button href="https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm?hl=en" target="_blank" >}}
Install uBlock Origin
{{< /button >}}

Once you've installed it, click on the extension and then the gear icon in the menu:

![uBlockOrigin Interface](/images/youtube-guide/adblock-popup.png)

The next page will open:

![uBlockOrigin Filter](/images/youtube-guide/adblock-filter.png)

Now copy and paste this element list to it and click _Apply Changes_.


```html
www.youtube.com##.on.ysm-btn-list-move-container
www.youtube.com###header > .ytd-guide-collapsible-section-entry-renderer.style-scope
www.youtube.com##ytd-mini-guide-entry-renderer.ytd-mini-guide-renderer.style-scope > .ytd-mini-guide-entry-renderer.style-scope.yt-simple-endpoint
www.youtube.com###logo
www.youtube.com###section-items > ytd-guide-entry-renderer.ytd-guide-collapsible-section-entry-renderer.style-scope > .ytd-guide-entry-renderer.style-scope.yt-simple-endpoint
```

You can see the differences in the left sidebar and the page logo; now it only has the buttons that you need. 

## Redirect: Change the default page
	
The only thing this extension does is redirect you to another link when you enter a website. We'll use this to make the default youtube page PocketTube's deck.

{{< button href="https://chromewebstore.google.com/detail/redirect/lfoabmjnfpgnafoagflchdgblfhnfccg" target="_blank" >}}
Install Redirect
{{< /button >}}

After installing it and clicking on the extension icon, this interface will pop up.

![Redirect Interface](/images/youtube-guide/redirect.png)

Create the following rules:

1. Without end slash:

From URL:

```html
https://www.youtube.com
```

To URL:

```html
https://www.youtube.com/#ysm-deck
```

2. With end slash:

From URL:
```html
https://www.youtube.com/
```

To URL:
```html
https://www.youtube.com/#ysm-deck
```

If you decided not to use PocketTube, you can change set _To Url_ to:
```html
https://www.youtube.com/feed/subscriptions
```

Now, whenever you go to the YouTube home page you'll be greeted with only the videos you want to see.



## Always use fullscreen

You can enter and exit fullscreen by pressing __F11__ in any browser. If you tend to wander around in your browser or other apps when you should be concentrating on the current video, this is a must. Very simple tip, but extremely effective.