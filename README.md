# Barnraiser-Prairie

## About Barnraiser

All the "Barnraiser-" projects in this repository were published at http://barnraiser.org/ a while ago. Although they had very promising features they were frozen and finally dropped for reasons which are explained [here](http://barnraiser.org/signing_off). According to this the main reason was the rise of similar products by companies with sufficient economic power to attract more users than a small enthusiastic bunch of coders.

Today we know where that evolution led and there's a tendency to move away from data-miners back to software under personal control. Funny enough this was exactly the intention of all projects at http://barnraiser.org/. We could say they were just a bit too far ahead of their time.

Fortunately they left the code of their open source projects available on their website. In order to preserve it and with the hope that some experienced coders will pick them up and adjust them to modern requirements I took the freedom to import them here. 

I'm not an experienced programmer, so there's not so much activity to be expected from my side. Much more this repository should be considerd as a base-camp for real coders who are able and willing to spend some time on these projects. I don't mind if they fork and develop on their own or ask for write-access to this repo. Although in the first case I would appreciate pull requests in order to keep the things together.

---

## About Prairie

This is the latest version prairie_20080922.tar.gz found at http://barnraiser.org/prairie. It was planned as a successor of the AROUNDMe Personal identity and AROUNDMe Identity server, which you can also find in my repository. When the latter ones were discontinued with the start of Prairie they already had reached version 1.2 and 1.3. Prairie itself never made it beyond alpha stage 0.1. 

The following is the original description from http://barnraiser.org/prairie

----

## Introducing Prairie
Forget all those different username and password combinations once and for all with Prairie; our Internet identity server.

Prairie is a lightweight OpenID based Internet identity server. Instead of registering at every web site with different username and password combinations you use your identity server to log you in.

Features
  - Simple profile webpage (Internet identity).
  - Install as a single user or a service to host many separate users.
  - Contact form.
  - DH-SHA1 support.
  - DH-SHA256 support.
  - OpenID 1.1 complient.
  - OpenID 2.0 complient.
  - Themed "skins" which can be easily downloaded and added.
  - Multi-lingual.
  - Free (GPL) software license.

## A case study; Identity page of Tom Calthrop
￼
One example of Prairie is the identity page of Tom Calthrop (maintainer of Prairie) and the founding director of Barnraiser.

The identity page is using an out of the box copy of Prairie.

http://tom.calthrop.info

## Technical considerations
Prairie requires a web server running either Apache 1.3/2.x or IIS5/IIS6 with PHP5.x installed including GD library, Curl and BCMath.

For multiple instances you will require wildcard sub-domains.

