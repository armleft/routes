


sudo apt install locales-all

add this to /etc/environment
```
LANGUAGE=en_US.UTF-8
LC_ALL=en_US.UTF-8
LANG=en_US.UTF-8
LC_CTYPE=en_US.UTF-8
```
reload, if not work run this:

locale-gen en_US.UTF-8
dpkg-reconfigure locales

or:

locale-gen en_US.UTF-8
export LANGUAGE=en_US.UTF-8
export LANG=en_US.UTF-8
export LC_ALL=en_US.UTF-8
locale-gen en_US.UTF-8
dpkg-reconfigure locales



