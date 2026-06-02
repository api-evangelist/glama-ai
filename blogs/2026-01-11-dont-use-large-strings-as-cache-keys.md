---
title: Don't Use Large Strings as Cache Keys
url: https://glama.ai/blog/2026-01-11-do-not-use-large-strings-as-cache-keys
date: '2026-01-11'
author: punkpeye
feed_url: https://glama.ai/blog/rss.xml
---
We cached parsed markdown to reduce CPU usage, but used the raw content as the key. Here's why that was a mistake and how we fixed it.
