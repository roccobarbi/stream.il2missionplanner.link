# stream.il2missionplanner.link
Il-2 Mission Planner Stream Backend

Originally forked from [stream.il2missionplanner.com](https://github.com/roccobarbi/stream.il2missionplanner.com).

## PLEASE NOTE: this repository is going to be entirely reengineered.

As suggested by the original repository's creator:

> As for the streaming functionality, I would not try to fix that. It is built using Redis and a Redis HTTP gateway called Webdis that uses HTTP Chunked Encoding to stream map updates. This technology was obsolete when I wrote it in 2016 has only gotten worse; it does not work well, according to user reports. I would suggest just reimplementing this feature yourself if you want it.

The plan is to research this kind of component and rewrite it from scratch using go (my preferred choice for server-side work) or python.