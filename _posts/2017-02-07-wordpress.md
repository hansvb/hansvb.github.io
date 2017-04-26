---
title: Which Wordpress and PhpMyAdmin to install?
---

Do Debian-packages make installing php-applications easier?

# Wordpress

At the time of writing the wordpress.org offered for download at https://wordpress.org/download/ is `4.7.2`.
Meanwhile `apt-cache show wordpress` shows me my Xubuntu installa `4.4.2`.

What exactly does the `wordpress`-package do?

It installs in `/usr/share/wordpress` and you must put a symlink from your `/var/www/html`-directory manually,
as explained on https://help.ubuntu.com/community/WordPress.

```
sudo ln -s /usr/share/wordpress /var/www/html/wordpress
```

So really, there are is big advantage here. Perhaps the database is already made?



