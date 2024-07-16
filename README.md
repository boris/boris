# Woot!

I've a docker image for tor: https://hub.docker.com/r/boris/tor

```docker run -d -p 9150:9150 boris/tor:latest```

And then, configure your connections (your browser, maybe?) to use a SOCKS proxy on `127.0.0.1:9150`

## Current version:
- Ubuntu: 0.4.8.9 - `docker run -d -p 9150:9150 boris/tor:0.4.8.9`
- Alpine: 0.4.8.12-r0 - `docker run -d -p 9150:9150 boris/tor:latest`
