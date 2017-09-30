---
layout: post
title:  "My Add-on Went live in minutes"
description: First Post by me
comments: true
<!-- author: Balaji -->
keywords: Mozilla, Add-on, Web Extension, AMO, MozillaTN, MozillaIN
---

A browser extension is a plug-in that extends the functionality of a web browser. Some of the Add-ons will enhace our browsing experience. I love to build software which will make the life easier. So I thought to develop one during the [SFD Hack17](https://reps.mozilla.org/e/mozillatn-sfd-extension-hackathon/) which is organised by MozillaTN on Software Freedom Day.

I always thinking about to manage my time effectively. I always running out of time. I will do lot of things say  Online **MOOCS**, Do **competitive Coding** **🙂** Finish a college Assignment :( . So I have to be productive to do all those things. So I was wondering how to monitor my time that I spend on different tasks. So the Idea cameup to build an add-on. 

My thougt is to make an icon in the toolbar. And Whenever we click the icon. The [Background script](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/manifest.json/background) will listen to it and exectute the [browser action](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/manifest.json/browser_action).  First I made a json file which handles the background scripts and browser action. I build an add-on with few dedicated timings tab like 20Secs, 5 and 15 Mins. I also made an input box where we can enter a specific time and based on that it will run the timing. 

Something like this.

&nbsp;
<img alt="Timeout add-on" src="{{ site.baseurl }}/assets/timeout_addon-1.png">
&nbsp; 

After some tweeking with JS and referring some [Tabs](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/API/tabs/executeScript) APIs like this. I finally got my add-on working.

&nbsp;
<img alt="Timeout add-on working" src="{{ site.baseurl }}/assets/timeout_addon-2.png">
&nbsp; 

After that I submitted my addon in addons.mozilla.org. To my Surprise my add-on went live and got an email from the Mozilla Add-ons Team. Check my add-on [Time-Out](https://addons.mozilla.org/en-US/firefox/addon/time-out-for-your-tasks/) here.

Within **5 minutes**, I get the following response:

<br>
<blockquote>

Hello,<br><br>

Your add-on, Time Out 0.2, has been approved and is now available for download in our gallery at https://addons.mozilla.org/addon/time-out-for-your-tasks/
<br><br>

Reviewer:<br>

Mozilla<br><br>

Comments:<br>
This version has been approved for the public.<br>
Thank you!<br><br>

If you want to respond please reply to this email or visit https://addons.mozilla.org/developers/addon/time-out-for-your-tasks/versions .<br><br>

To learn more about the review process, please visit https://developer.mozilla.org/en-US/Add-ons/AMO/Policy/Reviews<br><br>
Mozilla Add-ons Team<br>
https://addons.mozilla.org

</blockquote>

After that I found this in [Mozilla Add-ons Blog](https://blog.mozilla.org/addons/2017/09/21/review-wait-times-get-shorter/). Cheers to the Add-ons Team. So now the Add-ons built on the WebExtensions API will now be automatically reviewed. This is too awesome 🙂. 

### Let the world know
<div align="center">
<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">My Next <a href="https://twitter.com/MozWebExt">@MozWebExt</a>  went live in Less than a minute<a href="https://twitter.com/balaji2198/status/911788127534030848"> September 23, 2017</a></p>
</blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
</div>

<br>
Thanks to the AMO team & community contributors for all the knowledge shared plus mentoring and Mozilla Reps community for funding this event.