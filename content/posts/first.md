+++
title = 'First - Creating My Site'
date = 2024-01-30T15:45:20-08:00
draft = false
+++
> _Talk about how you made your site and why you chose the tools you did. Briefly explain one challenge you experienced in setting up this site and how you overcame it._

In creating my site, I originally went with the Hugo CMS one-click install, which seemed simple but ended up being quite complex. The first install didn't work correctly, because I had misconfigured github. A second install worked, but after several dead ends and a few rabbit holes, I found a very intimidating tutorial. This was clearly more than I needed for this exercise, so I abandoned the CMS. Next, I tried the Netlify one-click install for Hugo, since it was still my base of familiarity. It looked great but something was keeping the Netlify CLI from connecting to the Hugo repo on my computer, which meant I could not edit the site. I read through the Netlify CLI and Hugo deploy docs and support forums and decided the quickest option would be to start over (again) with Hugo directly on my computer, and then deploy to Netlify via github.

I initially planned to use Hugo on my machine to create a static html site and then just do a drag and drop deploy, but I found a third party tutorial that explained how to get the Hugo site to github, and have Netlify deploy directly from github. Luckily, I had already spent a good amount of time pushing sites around in github and adding things to my CLI in Terminal on my machine, which meant all of the integrations were ready to go. Once I pushed the first full version of this site, it built automagically and that felt really good.