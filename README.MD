This was a learning exercise for both Git and Redis.

I downloaded the source for Retwis (http://retwis.antirez.com/) and found that it didn't work.  If you tried to create an account, you'd get something like this:

Fatal error: unknown command '1229' in /var/virtual/retwis.antirez.com/httpdocs/redis.php on line 286

So I downloaded Predis 0.6.6 (https://github.com/nrk/predis/) and set to modifying Retwis to use Predis (instead of the legacy Redis.php it was using).

After an hour or so, it worked!  To complete the learning process, I set up a GitHub account, made a repository, and uploaded the source.  Enjoy!

Raphael
July 2011
raphael.crawfordmarks-at-gmail-dot-com
