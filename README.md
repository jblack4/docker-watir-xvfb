# Watir/Firefox in Docker via Xvfb

https://hub.docker.com/r/mipmip/watir-xvfb/

This Docker image provides a way to run headless Watir tests with
Firefox or actually Iceweasel because we're running Debian. I borrowed
the xvfb initializer from 
[markadams/chromium-xvfb](https://registry.hub.docker.com/u/markadams/chromium-xvfb/).

## Running the sample test

```
docker run watir ruby /app/test.rb
```
