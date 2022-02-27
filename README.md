# httpenv
Tiny HTTP server showing the environment variables on TCP 8888.

This can be used for various container learnings like how DNS round-robin works, rolling updates, etc.
It can be easier to use than something large and resource hungary like elasticsearch, while still providing
a way to check which container you're seeing in browser (or `curl`) by viewing the env vars it returns in HTTP.
