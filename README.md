# DokuWiki-Hubot Notifier
(Cloned and adapted from my https://github.com/vicendominguez/dokuwiki-hubothangups) 

A DokuWiki plugin that notifies to [Hubot-http-post-say](https://github.com/github/hubot-scripts/blob/master/src/scripts/http-post-say.coffee) API the wiki edits.

Setup
-----

1. Clone repository into your DokuWiku plugins folder, making the target folder name 'hubot'
```
$ git clone https://github.com/vicendominguez/dokuwiki-hubot.git hubot
```
2. In your DokuWiki Configuration Settings you will have a new fields to fill. Enter a URL to the [hubot http-post-say url](https://github.com/github/hubot-scripts/blob/master/src/scripts/http-post-say.coffee) and the id for the chat room.

3. Optionally, you can also define a comma-separated list of first-level namespaces to limit notifications to only those namespaces (without this setting, all namespaces will trigger notifications)


Requirements
------------

* DokuWiki
* [mandatory] PHP's cURL module
* http-post-say hubot plugin in you hubot install.

