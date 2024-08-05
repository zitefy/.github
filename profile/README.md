![bannerr](https://github.com/user-attachments/assets/25f6c1a7-dbf1-4aeb-b1df-a021d89172a9)

# [`zitefy`](https://zitefy.com/)
the link-in-bio tool for 2024, empowering you to create a unique webpage of your own, unrestricted, regardless of your web dev knowledge. This project was built at [FOSS Hack 4.0](https://fossunited.org/fosshack/2024).

<a href="https://www.producthunt.com/posts/zitefy?embed=true&utm_source=badge-featured&utm_medium=badge&utm_souce=badge-zitefy" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=476835&theme=dark" alt="zitefy - the&#0032;most&#0032;customizable&#0032;&#0038;&#0032;open&#0032;link&#0045;in&#0045;bio&#0032;tool&#0032;ever&#0044;&#0032;with&#0032;ai&#0033; | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

> 🚀 This has been shipped & is live [here](https://zitefy.com)! You can also [try the arcade demo](https://demo.zitefy.com).

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

This way, zitefy enables everyone to create a personal website! It doesn't matter whether you're a web dev, a designer, musician, artist, whatever. Just chat to zitechef and tell it what you want. It'll make the change for you!

## Keeping everything FOSS
This project was conceived, built & shipped at [FOSS Hack 4.0](), a hackathon for building free & open-source software. As such, we're commited to keeping everything FOSS. The entire project is built in mind with the philosophy of keeping everything open.

### The templates
Traditional approaches to link-in-bio tools have kept the templates closed source and sold them to users at a premium. Even with the premium, it's known that you can't edit the source code of the template, rather just use it. In zitefy, every template is inherently open source ([see repo](https://github.com/zitefy/templates)) and we also allow the end user to edit the template at the source code level.

When it comes to making templates anew, there is little to no info on how to do that on all the prominent link-in-bio tools. However, we have documented the entire process to make sure anyone can contribute templates ([see guide](https://github.com/zitefy/templates?tab=readme-ov-file#templating-guide)) in the spirit of welcoming anyone to make a template for others to use! The server is written in a way that any web dev can easily decode the algorithm themselves ([see code](https://github.com/zitefy/server/blob/main/scripts/builder.js)), and it's also been [documented](https://github.com/zitefy/templates?tab=readme-ov-file#the-html-creation-algorithm) for newbies.

### Web portal & API
The [website](https://zitefy.com) is open-source ([see code](https://github.com/zitefy/portal)) as is the [API](https://api.zitefy.com/docs/#/) behind it ([see code](https://github.com/zitefy/server)). You can report issues and/or improve the zitefy stack by contributing to these. 

## Data privacy
We only aim to keep user data private. This doesn't even include the site data of users. If you create a site on zitefy, it will be available to anyone to see & use. This is a reminder not to store any personal or sensitive info in your site source code. Of course, your user data like your social handles, phone number, email, etc aren't visible to everyone and are secured behind your own private key & password, but the stuff in all sites are accessible publicly.

Your personal data is not shared with zitechef either. The template code is structured in a way such that the LLM only gets the HTML, CSS & JS that is shown in the editor. Your personal info is added later in the server when you save or refresh the site. None of the info that you select in the web editor is passed to the LLM. The template guide for developers also suggests that they follow this pattern for maximum compatiblity. So, templates by third party devs will also be secure.

## Source code
The source code is split across three different repositories. Here's what they are:

* [server](https://github.com/zitefy/server): is the central server where the site is hosted and the api endpoints reside, basically the backbone of the whole thing. it's written in rust using the actix web framework
* [portal](https://github.com/zitefy/portal): is the web app you see at [zitefy.com](https://zitefy.com/). it's written in typescript with solid.js.
* [templates](https://github.com/zitefy/templates): this repo houses all the templates available in zitefy. you can add a new template of your own by contributing here!

## License
All repositories are licensed under the MIT License, see [LICENSE](https://github.com/zitefy/portal/blob/main/LICENSE) for more information.

## Citations & Acknowledgements
This project wouldn't exist without these resources:

* [actix-web](https://actix.rs/)
* [solid.js](https://www.solidjs.com/)
* [bun](https://bun.sh)
* [puppeteer](https://pptr.dev/)

## FAQ
*FOSSHack Questionnaire:*

Q. What was the initial stage of the project?

> The initial idea of the project stemmed from the notion that everyone should be able to create a personal website for themselves.
> Initially, at the start of FOSS Hack, the project had a logo & a UI design. We also had a mental image of the server's architecture to begin with.

Q. What stage is it in now?

> It's ~90% complete, with v0.1 beta shipped! :rocket: All the functionalities work, but there are some issues on systems with lower memory, such as the VPS it's being run on now. The whole application is slow at the moment.

Q. How did you get there?

> The authors are web developers who have once gone through the ordeal of having to build a personal website from scratch without no base code to begin with. This is a tedious process for many and inaccessible for many more who don't know web dev. Existing link-in-bio platforms are ultimately limited when it comes to customizability.
> We thus started working on this idea with the notion that everyone deserves their place on the web, with their own personal webpage or website.

Q. What is working/not working?

> The search and sort by filters in the templates explorer isn't working. The [API for search](https://api.zitefy.com/docs/#/template/search_templates) is ready, but we haven't integrated it with the portal yet.
> Everything except the site preview in the editor is working. We were able to get this working in our local machine with an octa core processor & 16 GB RAM as well ([see video](https://youtu.be/zrExP-ZH0xY?si=4Q8iMhf6X0D6h-_e&t=39)) but couldn't get it to work in the prod VPS with a single core CPU & 1GB RAM. See [this issue](https://github.com/zitefy/server/issues/4) to know more.
> RIght now, there also seems to be a problem with zitechef's responses due to inefficient tokenization of messages ([see issue](https://github.com/zitefy/portal/issues/4)), but that can be quickly sorted.

## Future
Refinement. The stack has some points that need to be refined, like the responsiveness, mem footprint, etc. When it comes to features, we'd like:
* the ability for someone to add a template from the web editor directly, without having to contribute explicitly via the github repo.
* the UI of the editor to be improved so that it allows more values to be displayed and selected
* more personal info like projects, images, etc.
