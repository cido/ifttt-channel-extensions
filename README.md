IFTTT Channel Extensions
========================

Deprecated! Use the [Maker Channel](https://ifttt.com/maker) instead
--------------------------------------------------------------------

IFTTT has recently introduced [Maker Channel](https://ifttt.com/maker) which makes it possible to trigger and react to webhooks. As that is almost exactly what this project tried to do with the WordPress hacking, that makes this project now officially deprecated. I'm quite sure you'll get further nowadays with the Maker Channel, and possibly some lightweight scripting code that deals with those webhooks.

I have some interesting project ideas bubbling regarding the Maker Channel and its possibilities, so if you're into that kind of stuff, stay tuned :)

Original description
--------------------

Create your own custom IFTTT recipes/channels/actions/whatever with PHP.

This project started as fork from the [ifttt-webhook](https://github.com/mapkyca/ifttt-webhook) project. I wanted to extend IFTTT functions with code. ifttt-webhook uses a clever dummy Wordpress installation to fool IFTTT to think that it is actually posting new blog posts, when it is actually sending out webhook requests. However I didn't like the boilerplate involved, and would have preferred more cleaner code-based solution. So I refactored the existing code to use local plugins and actions instead of separate webhook requests.

Usage instructions
------------------

None provided, sorry. If you have any problems, feel free to open an issue!

Licence
-------

Licenced under GPL. Some portions of the code are from wordpress itself.
