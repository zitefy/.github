![bannerr](https://github.com/user-attachments/assets/25f6c1a7-dbf1-4aeb-b1df-a021d89172a9)

# [`zitefy`](https://zitefy.com/)
the link-in-bio tool for 2024, empowering you to create a unique webpage of your own, unrestricted, regardless of your web dev knowledge.

🎞️ [**Watch in full quality on YouTube**](https://youtu.be/zrExP-ZH0xY)

https://github.com/user-attachments/assets/b553b411-93e1-4271-a97c-40f17bdad80b

## What's this?
This, at it's core, is an open-source link-in-bio tool. But unike traditional counterparts like [linktree](https://linktree.com), [bento](https://bento.me/en/home) or even the open-source [librelinks](https://www.librelinks.me/), zitefy takes a different approach which offers unparalleled customizability for creating your unique websites.

On the surface, zitefy seems just like any other link-in-bio tool. A big fat web app shows you different templates, you choose one to create a site, adjust what data you want to be shown, and save it. You get a unique URL for your site, which you can share everywhere.

## duh, what's the deal then?
Well, all of the link-in-bio tools give you a big UI to edit the template to *make it unique* to you. But really, is it truly unique to you? At the end of the day, you're constrained by the options available in the editor, not your creativity.

In zitefy, you're constrained only by your creativity! That doesn't make much sense now does it? Read on...

## The approach
In zitefy, everything is open to all. When you want to create a site from a template, you get the full source code of the template in your browser!  You can then choose what info you want displayed in the site, just like a traditional link-in-bio tool.

You can edit the code any way you want to your heart's content. The sky is the limit! Once you're done, just hit save, go back and activate the site. Your new site will be live! This way, none of the code of the page is hidden behind a mask, making everything about it fully open and allowing you to carve your page to your liking.

### I don't know how to code
Don't worry, we got you covered! We've thought about everyone. You don't need to know how to code in order to edit a template, you just need to know how to chat! Once you're in the editor, select all that you want displayed in the site. Then, click the small moustache-like icon on the bottom right hand corner of your screen.

Say hi to zitechef! It's your AI chef who'll cook up your site for you, the way you ask! Again, the sky's the limit! zitechef is basically [Claude 3.5 Sonnet](https://claude.ai/) under the hood, so it's very good at coding tasks. Right now, this doesn't have the capability to process images, but that's coming soon!

This way, zitefy enables everyone to create a personal website! It doesn't matter whether you're a web dev, a designer, musician, artist, whatever. Just chat to zitechef and tell it what you want.

## Source code
The source code is split across three different repositories. Here's what they are:

* [server](https://github.com/zitefy/server): is the central server where the site is hosted and the api endpoints reside, basically the backbone of the whole thing. it's written in rust using the actix web framework
* [portal](https://github.com/zitefy/portal): is the web app you see at [zitefy.com](https://zitefy.com/). it's written in typescript with solid.js.
* [templates](https://github.com/zitefy/templates): this repo houses all the templates available in zitefy. you can add a new template of your own by contributing here!
