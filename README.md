# DokuWiki-Hubot-Hangups

A DokuWiki plugin that notifies to Hubot-Hangups API the wiki edits.

Setup
-----

1. Clone repository into your DokuWiku plugins folder, making the target folder name 'hubothangups'
```
$ git clone https://github.com/vicendominguez   hubothangups
```
2. In your DokuWiki Configuration Settings, enter a URL to the hubot-hunagups API and the id for the chat room.

3. Optionally, you can also define a comma-separated list of first-level namespaces to limit notifications to only those namespaces (without this setting, all namespaces will trigger notifications)


Requirements
------------

* DokuWiki
* [mandatory] PHP's cURL module
