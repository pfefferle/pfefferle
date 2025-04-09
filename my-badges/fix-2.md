<img src="https://my-badges.github.io/my-badges/fix-2.png" alt="I did 2 sequential fixes." title="I did 2 sequential fixes." width="128">
<strong>I did 2 sequential fixes.</strong>
<br><br>

Commits:

- <a href="https://github.com/pfefferle/wordpress-activitypub/commit/62f7b484c868094c7ee3e58fb87635734f3563c5">62f7b48</a>: Fix: (Pixelfed) Follow (#1501)

* Fix: Pixelfed Follow

* fix test

* Add changelog

* cleanup other fields too

* Test that `set_to` will not be replaced by object if already set by activity

* improve tests

props @obenland

---------

Co-authored-by: Automattic Bot <sysops+ghmatticbot@automattic.com>
- <a href="https://github.com/pfefferle/wordpress-activitypub/commit/e394264cbb0fa135ee3d364d64812cd8af8a959c">e394264</a>: Fix: Announces (#1500)

* Fix: Announces

With the re-write of how we store Activities in the Outbox, the Announces do no longer work. This PR fixes that.

* Update includes/class-scheduler.php

Co-authored-by: Konstantin Obenland <obenland@gmx.de>

* simplify namings

* Add unittests

* Add changelog

---------

Co-authored-by: Konstantin Obenland <obenland@gmx.de>
Co-authored-by: Automattic Bot <sysops+ghmatticbot@automattic.com>


Created by <a href="https://github.com/my-badges/my-badges">My Badges</a>