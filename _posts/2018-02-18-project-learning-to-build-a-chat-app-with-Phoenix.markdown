---
layout: post
title:  "Project: Building a chat app with Phoenix"
date:   2018-02-18 13:00:00
categories: web development
---

![Screenshot of application]({{ "/assets/screencapture-babble-herokuapp-chat.png" | absolute_url }}) <br>
*The image is a screencapture taken of a chat during a live presentation of the project.*

Last month when I participated in a [hackathon][hackathon-post] I also learned about a new framework, new to me that is, from one of my teammates. She, a computer science student, showed me a chat application that she had built for class. I had never heard of this framework before so I was intrigued and thought to myself that I would like to put that on my list of things to try to learn.

So what is Phoenix? It is a framework that uses the Elixir programming language, which looks a lot like Ruby on Rails. Just like Ruby we have a router, models, views, and controllers. We also have HTML, CSS, and Javascript. (Checkout the [Phoenix docs overview][Phoenix-overview] page if you care to dive deeper. [Elixir][Elixir-docs] also has their own documentation.) So it seems like the front-end and back-end are married together in a nice & neat package.
Sweeeet!!

I wanted to just build a basic application to become more familiar with this technology. Nothing fancy.

I did some research, and by that I mean I searched on Google, and found a great [Youtube tutorial][Youtube-tutorial] that demonstrated through the process step-by-step in 3 video segments. This wasn't the first of what I found in my search but it most definitely was the most helpful. There are a lot of steps in the process, and I'll say that authentication took the most time.

The project that I've titled 'Babble' is a work in progress. I may or may not expand on it, and personalize it more. There are a couple of features that are on the 'nice to have' wishlist, such as:

• Show Username instead of email address after the 'Hello there' message, and within the chat dialogue box.

• Currently once a user leaves the chat page, the previous chat is not saved.

• Currently the app isn't exclusive to specific user groups, whomever is signed-in is seen as online.

The experience was good to become aware of all that goes into building a chat application.

Feel free to try out the application that I built [here][babble-app] yourself, and you never know whom you might find online with you.

If your curious about the code you can checkout it on my [Github][github-repo] repo.

[hackathon-post]: https://aliciapflaumer.github.io/alicia/web/development/hackathon/2018/01/26/getting-out-of-my-own-way.html
[Phoenix-overview]: https://hexdocs.pm/phoenix/overview.html
[Elixir-docs]: https://elixir-lang.org/
[Youtube-tutorial]: https://www.youtube.com/watch?v=irDC1nWKhZ8
[babble-app]: https://babble.herokuapp.com/
[github-repo]: https://github.com/aliciapflaumer/babble
