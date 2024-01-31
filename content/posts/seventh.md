+++
title = 'Seventh - redirect'
date = 2024-01-30T17:24:37-08:00
draft = false
+++
> _How would you set up an http 301 status redirect from “/netlify/anything” on your site, to https://www.google.com/search?q=anything. Please provide the redirect formatting here. Now, how about a proxy redirect? Please add that proxy redirect rule directly to your site._

Using a 301 status redirect in a `_redirect` file

```
# Redirect with a 301
/netlify/anything         https://www.google.com/search?q=anything              301
```

Using the 301 status redirect in a `netlify.toml` file

```
[[redirects]]
from = "/netlify/anything"
to = "https://www.google.com/search?q=anything"
status = 301

```


Link to proxy redirect [https://rainbow-cat-4d4d00.netlify.app/netlify/anything](https://rainbow-cat-4d4d00.netlify.app/netlify/anything)