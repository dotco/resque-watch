PHP Resque Watch
============

A simple command line tool to output status updates on your Resque queue. 

Simply install on a machine, edit `resque-watch.php` and change the Redis server location if necessary, and run:

```bash
php resque-watch.php
```

Resque Watch will spit out your queue names, queue sizes, processed jobs, failed jobs, worker names and stats, and last failures.
