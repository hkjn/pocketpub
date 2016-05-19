# pocketpub

Repo pocketpub is a tool for publicly displaying Pocket items.

## Status

Early exploration

## TODOs

* Use the v3 API (https://getpocket.com/developer/docs/v3/retrieve) to grab all items and their tags
* Serve all items tagged `:tag` at `/get/tag/:tag`
* Serve all items with `:search` in title or URL at `/get/search/:search`
* Should cache data with each read to memory and maybe disk to serve as a cache if pocket is slow, down, or disappears.

