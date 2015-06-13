# DokuWiki-Hubot-Hangups

A DokuWiki plugin that notifies to [Hubot-Hangups](https://github.com/groupby/hubot-hangups) API the wiki edits.

Setup
-----

1. Clone repository into your DokuWiku plugins folder, making the target folder name 'hubothangups'
```
$ git clone https://github.com/vicendominguez/dokuwiki-hubothangups.git hubothangups
```
2. In your DokuWiki Configuration Settings, enter a URL to the [hubot-hangups](https://github.com/groupby/hubot-hangups) API and the id for the chat room.

3. Optionally, you can also define a comma-separated list of first-level namespaces to limit notifications to only those namespaces (without this setting, all namespaces will trigger notifications)


Requirements
------------

* DokuWiki
* [mandatory] PHP's cURL module

Hubot-hangups info
------------------

For getting fast-info of the [hubot-hangups](https://github.com/groupby/hubot-hangups) API and its conversationId field please read this thread: https://github.com/groupby/hubot-hangups/issues/27
