watchpeopledie-bot
==================

For transferring youtube videos to liveleak

as suggested in /r/watchpeopledie

Complete
--------

Given a username, password, title, body text and filename the *liveleak* script will upload the file to Amazon S3 and then on LiveLeak, tag it with "reddit" and "/r/watchpeopledie", say it's from the UK (where I am), put it in the "other" category (because I will have no idea of the subject), give it a Mature rating and set it as happening today.

TODO
----

* Scan reddit for new posts
* Download the clip from youtube
* Put it all together

I will be using youtube-dl for downloading from youtube which I know works. It also downloads from some other sites but I've not looked into that.

