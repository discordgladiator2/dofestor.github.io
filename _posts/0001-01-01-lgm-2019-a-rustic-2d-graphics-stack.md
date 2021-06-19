---
title: "LGM 2019 – A Rustic 2D graphics stack"
image: "https:\/\/i.ytimg.com\/vi\/wMoS0QHBoHM\/hqdefault.jpg"
vid_id: "wMoS0QHBoHM"
categories: "Science-Technology"
tags: ["LGM","Libre Graphics","Libre Graphics Meeting"]
date: "2021-06-19T15:44:44+03:00"
vid_date: "2019-07-17T19:58:04Z"
duration: "PT22M24S"
viewcount: "2011"
likeCount: "41"
dislikeCount: "0"
channel: "Libre Graphics Meeting"
---
{% raw %}Colin Rofls, Raph Levien<br />A Rustic 2D graphics stack<br /><br />2D graphics is core infrastructure to most graphics software, and is needed for UI and games as well. Older techniques, primarily based on software rendering, aren’t performant in a modern GPU-based environment. Portability is also a concern, especially now that the web is emerging as a viable target for native code. When choosing 2D graphics technology for the Rust language, we have an opportunity to do things right, but also a challenge, in that none of the existing libraries are quite appropriate. This work fills that gap. At the core is piet (named after Piet Mondrian), a 2D graphics abstraction that can have multiple back-ends to implement the actual drawing. In particular, using the platform-native 2D graphics engine makes applications build fast and small. On the web, drawing is done with the web canvas. In the future, we expect high performance GPU based 2D drawing built in Rust, likely including WebRender and Pathfinder.<br /><br />On top of piet is druid, a very lightweight UI toolkit, optimized for performance and suitable for games and other graphics-intensive applications. A goal is adding UI to a Rust app with minimal boilerplate, so that “cargo run” pops up a window quickly..<br /><br />Raph Levien is a long-time open source developer of graphical software, with contributions including Gimp, Ghostscript, font tools, major improvements in the Android text stack, and xi-editor. His PhD from UC Berkeley is on Spiro, an interpolating spline tuned for font design. His Inconsolata font was designed using those tools. Based in Berkeley, CA, after 11 years at Google, he is now independently working on a variety of projects, including Rust graphics and sound infrastructure.<br /><br /><a rel="nofollow" target="blank" href="https://github.com/linebender/piet">https://github.com/linebender/piet</a><br /><br />This presentation was recorded on Thursday, 30th May 2019 as part of Libre Graphics Meeting 2019, at the Hochschule der Bildenden Künste Saar in Saarbruecken, Germany. To learn more, see <a rel="nofollow" target="blank" href="https://libregraphicsmeeting.org/2019/.">https://libregraphicsmeeting.org/2019/.</a>{% endraw %}
