---
layout: post
title:  "Hello world!"
date:   2018-05-18 18:00:00 +0100
categories: random
---
Hello there. Here I'll blog about, hm, anything.

For starters, I'll release a series of posts on how I created this blog, more specifically on the technology used for it being here.

This is a static blog, built using [Jekyll][jekyll-gh]. Jekyll is a Ruby gem which transforms all your content written in Markdown and Liquid templates into a static website (HTML and CSS). The source code for this blog can be found [here][gabrielparreiras-jekyll-gh].

The blog is hosted on AWS and all AWS services are managed using Cloudformation (CFN). For generating CFN templates I am using [Sparkleformation][sfn-gh] (SFN). SFN is also a Ruby gem which has its own Ruby-based DSL for representing CFN templates. It makes templates reusable and simpler to read and write. The source code for the SFN used to build this infrastructure can be found [here][gabrielparreiras-sfn-gh].

I'll try to cover as well some CI/CD topics, and my intent is that both repositories will be tested, built and deployed by TravisCI.

That's it for now.

[jekyll-gh]: https://github.com/jekyll/jekyll
[gabrielparreiras-jekyll-gh]: https://github.com/gmpify/gabrielparreiras.com-blog
[sfn-gh]: https://github.com/sparkleformation/sfn
[gabrielparreiras-sfn-gh]: https://github.com/gmpify/gabrielparreiras.com-sfn
