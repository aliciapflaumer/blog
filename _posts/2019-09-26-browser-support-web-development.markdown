---
layout: post
title: "6 Browsers for Web Developers: Which one do you use?"
date: 2019-09-26 12:00:00
categories: web
---

This post is about the various web browsers that software developers have to choose from – picking a favorite gets to be some kind of a lottery. Once a developer gets used to one, they may neglect the others - until it comes time for testing. Admit it, this is familiar to you too, right?

According to W3Counter, **Chrome** is the [most popular browser](https://www.w3counter.com/globalstats.php){:target="_blank"} amongst users followed by **Safari** as second, then **Internet Explorer** and **Edge**, **FireFox**, and lastly **Opera**.

In this article I have layed out the specifications for each common browser, including the initial release year, the programming languages the software was written in, and the engine that renders the webpage. [*Source: Wikipedia*]

**1. Google Chrome**<br>
  Initial release year: 2008<br>
  Programming languages: C, C++, JavaScript, Java (Android app only), Python<br>
  Engines: WebKit, Chrome V8, Blink<br>
  Mobile version: Yes

*Chrome dev tools:*<br>
![Chrome-Dev-Tools]({{ "/assets/chrome-dev-tools.jpg" | absolute_url }})

The common features between each browser's developer console, is a select option – a tool that is used to inspect a specific element on the webpage – and the elements tab – to help test new CSS, and hide parts that may be causing an issue with rendering of the page.

All of the browsers have the ability to test responsiveness across multiple screen sizes - a very helpful tool indeed.

**2. Apple Safari**<br>
  Initial release year: 2003<br>
  Programming languages: C++, Objective-C<br>
  Engines: Webkit, Nitro<br>
  Mobile version: Yes

*Safari dev tools:*<br>
![Safari-Dev-Tools]({{ "/assets/safari-dev-tools.jpg" | absolute_url }})

While the console seems to be similiar across all browsers, some different features standout in a few. Such as, Safari's tool to add rulers to a page:

![Safari-Console-Tools]({{ "/assets/safari-console-rulers.jpg" | absolute_url }})

**3. Microsoft Internet Explorer**<br>
  Initial release year: 1995<br>
  Programming languages: C++<br>
  Engine: Trident in first release of IE 4.0 in 1997<br>
  Mobile version: No<br>
  *Discontinued, still maintained for Windows*<br>
  *No longer supported for macOS*<br>

As a developer on a macOS, one may find it difficult to debug IE specific display bugs, if you don't have a PC with Internet Explorer handy. There IS a way to turn your mac into a virtual PC with an application called [Parallels](https://www.parallels.com/landingpage/pd/general/){:target="_blank"}. The software has been around for awhile, but there is a catch – although there is a free trial to start, you ultimately would need to buy a license to use the application.

It seems Microsoft is slowly trying to move people away from IE and onto their new Edge browser. So hopefully we won't have to endure the virtual pain of including [IE conditional comments](https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/compatibility/hh801214(v=vs.85)){:target="_blank"} in our HTML markup much longer:
```html
<html>
  <!--[if IE]>
    This content is ignored in IE10 and other browsers.
    In older versions of IE it renders as part of the page.
  <![endif]-->
</html>
```

Though, there is some good news macOS users! Earlier this year [Microsoft released a beta version](https://blogs.windows.com/msedgedev/2019/05/20/microsoft-edge-macos-canary-preview/){:target="_blank"} of Edge for mac – the default search engine is Microsoft's own Bing. The mac version of the browser is supposed to have the same look and feel as the Windows version. So, hooray Microsoft!

**4. Microsoft Edge**<br>
  Initial release year:<br>
    Windows 10, Xbox One: 2015<br>
    Android and iOS: 2017<br>
    macOS: 2019<br>
  Programming languages: C++, C#<br>
  Engines: EdgeHTML (Chromium-based using Blink), Chakra (JScript)<br>
  Mobile version: Yes

*Edge dev tools:*<br>
![Edge-Dev-Tools]({{ "/assets/edge-dev-tools.jpg" | absolute_url }})

**5. Mozilla Firefox**<br>
  Initial release year: 2002<br>
  Programming languages: JavaScript, Cascading Style Sheets, C, C++, XBL, XUL<br>
  Engines: SpiderMonkey, Gecko<br>
  Mobile version: Yes

*FireFox dev tools:*<br>
![Firefox-Dev-Tools]({{ "/assets/firefox-dev-tools.jpg" | absolute_url }})

Mozilla has their own alignment tool, when using the selection tool horizontal and verical hashed lines are shown – I suppose this could be useful, too.

![Mozilla-Inspector]({{ "/assets/mozilla-inspector-screenshot.jpg" | absolute_url }})

**6. Opera**<br>
  Initial release year: 1995<br>
  Programming languages: C++<br>
  Engines: Chrome V8, Blink<br>

Opera uses the same rendering engine as **Chrome** – so the developer console looks the same there too. Earlier this year, the Opera team released a version they referred to as [Reborn 3](https://blogs.opera.com/desktop/2019/02/opera-r-3-developer){:target="_blank"}, focused on the browsers "look and functionality", according to their blog.

*Opera dev tools:*<br>
![Opera-Dev-Tools]({{ "/assets/opera-dev-tools.jpg" | absolute_url }})

Well, that's about it. I hope this is helpful and maybe you'll be motivated to do a little exploring of your own with a new browser that you regularly do not use.

*Images: Screencaptures of individual webpages by Alicia Pflaumer on macOS*