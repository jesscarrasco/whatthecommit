whatthecommit - sieiro edition
==============================

An unoffical command client to fetch a random and silly commit message from
[whatthecommit.com][wtc], spiced up with siero content.

> For the sources of [whatthecommit.com][wtc] see
> https://github.com/ngerakines/commitment

FAQ
---

#### Is it useful?

Yeah, sure, I mean it's perfect for those cases where you
haven't committed a change in ages and feel too important to use
`git add -i`, so `git commit -am "$(sieirocommits)"` to the rescue :wink:

#### How do I install it?

To get up and running as fast as possbile run

    curl -L http://github.com/jesscarrasco/whatthecommit/raw/master/sieirocommits > /usr/local/bin/sieirocommits && chmod 0755 !#:3

#### Are there any options?

Sure, check `whatthecommit -h` for usage and options.
