# Replay Mode

I really like [[activitypub]] apps like Lemmy and Mastodon because I can script against the public with no key, which allows me to write fun web tools.

One web tool I would like would be a "replay mode" for events. I watch a lot of sports, and participate in a lot of live discussions with people while watching those sports. I would like a website that allows me to "replay" a live sports event, and see the tweets synced with the event as I'm watching it.

For example, if I live in the Pacific Standard Time zone, the FIFA Women's World Cup final is at 3 am local time, which is a hard time to get up. Today, I can't interact with social media while I watch the match unless I stay up (or get up early) -- all of the threads have been updated with the final score.

With replay mode, we would do a query to get all of the toots for a single user from the given time frame. Then, once a minute, we can output the next batch of toots to the screen, simulating what it was like on the service during the event.
