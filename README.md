# gsynch
Synchronize filesystems via google drive. Allows remote sites behind firewalls to stay in synch.

Basic idea:  make a bunch of folders and lists on a shared google drive
that can be accessed through `rclone`. Each local site runs `cron` jobs
that keeps things synchronized.
