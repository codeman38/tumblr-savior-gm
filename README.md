# Tumblr Savior for Greasemonkey

## What does it do?

I'll just quote the extension's original developer, Bjorn Stromberg:

"Tired of posts about the iPhone filling up your dashboard? Hate hearing about some athlete's latest blunders? If you just want to hide posts about certain topics, Tumblr Savior is here to save you. Just add your most despised terms to the black list and Tumblr Savior will valiantly protect your delicate sensibilities. And if you wonder what got hidden, there’s a handy link to show you."

## What's different from the original version?

Here's what's different from the browser-extension version of Tumblr Savior ([binaries](http://bjornstar.com/tumblr-savior) / [source](https://github.com/bjornstar/Tumblr-Savior)):

* It actually works outside the context of the browser extension-- in fact, some of the extension-specific code has been eliminated.

* CSS transition effects on hidden posts are disabled, because they've been known to bog things down on some machines-- and because they don't work with the new Tumblr layout anyway, besides.

* As in my previous "Tumblr Savior With A Fork In It", it's possible to include a logical 'and' operator by using an ampersand within a blacklist/whitelist string. (For instance, adding "george wendt&beans" to the blacklist will only block posts containing both "george wendt" and "beans".)

## Why use this version instead?

* Because Greasemonkey scripts are even more universal than browser-specific extensions (and less finicky with API changes).

* Because the version bundled in the browser extension isn't lightweight *enough* for some people.

* Because the original can't do logical 'and' operations on keywords.

## How do I install it?

[Just follow this link right here!](https://raw.github.com/codeman38/tumblr-savior-gm/master/tumblr-savior.user.js) Then be sure to modify the default settings of 'listBlack' and 'listWhite' to something that's a bit more useful and a bit less of a fandom in-joke.