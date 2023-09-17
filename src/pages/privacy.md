---
layout: ../layouts/Layout.astro
---

## Tangent

### What we collect

Nothing

This means no update checking, please update (`nix profile upgrade '.*'`) as often as possible because the web browser is by far [the most vulnerable component of your desktop](https://webkitgtk.org/security.html).

### Others

Tangent is not your privacy browser. An unfingerprintable browser must be the same for everyone and have many people using it. Please use [Tor Browser](https://torproject.org) for this purpose.

## Oxymoron

It's like any other ActivityPub software, you can [search the GitHub for `sql` to find out the exact data we store](https://github.com/search?q=repo%3Amollersuite%2Foxymoron%20sql&type=code) (Spoiler alert: Your posts, your reactions, your password (Argon2), and your profile info. Fuck else did you expect)

Oxymoron does not have bookmarks because Methodsave exists. We think bookmarks are too secret for us to store anyway.

To protect moron.center from reaching [free plan limits](https://workers.cloudflare.com/#plans) instantly, Oxymoron does not yet proxy images or videos. Your IP and user agent will be exposed to the instance hosting them when loading the image. We might add a manual image loading setting if this becomes a problem, but most instances aren't evil, and the ones that are we should have blocked.

Oxymoron's flagship instance, moron.center, has its object storage ([R2](https://developers.cloudflare.com/r2)), frontend, and backend hosted by Cloudflare.

moron.center and r2.moron.center are proxied by Cloudflare as well.

ActivityPub is open by design. Anyone and anything can download your public posts.

## Methodsave

Methodsave scrapes what you Save so that they can survive deletion by the author. [Imagine if a note depended on a tweet and then their account was just deleted!](https://github.com/mollersuite/mollermethod/blob/9b3565dcc214f46a63885d2c753d43d10fb32670/deploy.sh#L1) [You'd be unable to figure out shit!](https://owo.community/notes/9iuoqpdvb2)

On Android, this is done via the Accessblity API. On PC, this is done by API calls to the website.

## Method Desktop

Defaults to Google's STUN/TURN servers. They'll get your IP (the purpose of STUN/TURN is literally to return your IP)
