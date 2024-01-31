+++
title = 'Second - What did you think of our service?'
date = 2024-01-30T15:55:36-08:00
draft = false
+++
> _What did you think of our service during the time you used it? Provide some constructive criticism or some features that impressed you._

I have been impressed but somewhat frustrated with the Netlify service! Deploying was very simple using the Netlify web app, but the walkthroughs, tutorials, and docs I encounted covered (1) Initial setup of the framework and then went directly to (2) deploying the completed site, but with very little discussion of actually editing the code or working with the frameworks that had been installed. Most of the help content seems to point directly to what I eventually did--create the site on my machine completely, then deploy a completed site to Netlify. The control over the running sites in the Netlify app is impressive and comprehensive, and the Netlify CLI and its integration with Github were simple to install and comprehensive. But the Netlify CLI "Dev" command, which should have given me the ability to work on my site from my machine in the CLI, crashed multiple times, eventually taking down my machine and necessitating a restart. To be clear: I'm positive there was some user error involved, but I walked a frustrating path for a time during this exercise. 

Once I realized that Netlify Dev did not get along with Golang, and moved towards my usual Hugo site development method of building the site on my local machine, deployment was a dream. I connected my github and Netlify, then created the repo and pushed to github. The netlify app walked me through each step, and the build process was very simple. Watching edits go through after I pushed them and netlify rebuilt the site using Hugo was very satisfying. 