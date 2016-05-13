# spawner-bin

Linux version
=======
Statically linked build of the Spawner program is available (host platform Debian/8.4)
* For i386 build see linux-i386/sp
* For amd64 build see linux-amd64/sp

Both shall work fine in 64-bit environments.

To make delegate runner work (option `-u username`), put `sp` binary to the `/usr/local/bin/` directory (or create valid symbolic link to the `sp` binary).
