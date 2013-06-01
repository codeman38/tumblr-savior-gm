# Tumblr Savior for Greasemonkey

## What does it do?

I'll just quote the extension's original developer, Bjorn Stromberg:

"Tired of posts about the iPhone filling up your dashboard? Hate hearing about some athlete's latest blunders? If you just want to hide posts about certain topics, Tumblr Savior is here to save you. Just add your most despised terms to the black list and Tumblr Savior will valiantly protect your delicate sensibilities. And if you wonder what got hidden, there’s a handy link to show you."

## What's different from the original version?

Here's what's different from the browser-extension version of Tumblr Savior ([binaries](http://bjornstar.com/tumblr-savior) / [source](https://github.com/bjornstar/Tumblr-Savior)):

* It actually works outside the context of the browser extension-- in fact, some of the extension-specific code has been eliminated.

* As in my previous "Tumblr Savior With A Fork In It", it's possible to include a logical 'and' operator by using an ampersand within a blacklist/whitelist string. (For instance, adding "george wendt&beans" to the blacklist will only block posts containing both "george wendt" and "beans".)

* The link to unhide a post can now be activated via the keyboard, for non-mouse users.

* Keyboard navigation using the 'j' and 'k' keys is no longer broken when a post is hidden.

* A new option, 'hide_own_posts', has been added to the settings object; if set to true, this will cause the blacklist and whitelist to apply to posts that you've made as well as others' posts.

## Why use this version instead?

* Because Greasemonkey scripts are even more universal than browser-specific extensions (and less finicky with API changes).

* Because the version bundled in the browser extension isn't lightweight *enough* for some people.

* Because the original can't do logical 'and' operations on keywords.

* Because you're a frequent keyboard user.

* Because you're triggered by something that you yourself have posted about.

## How do I install it?

[Just follow this link right here!](https://raw.github.com/codeman38/tumblr-savior-gm/master/tumblr-savior.user.js) Then be sure to modify the default settings of 'listBlack' and 'listWhite' to something that's a bit more useful and a bit less of a fandom in-joke.