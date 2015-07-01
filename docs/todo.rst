====
ToDo
====

- add howto about supervisior to docs
- add nice bashrc
- do we need a get_ip_script ?

Network
-------

default is now nat, with forwarding port 80, we should add also a port forward
for port 22 [ssh].

there is nginx pre-installed and configured, if you change network to
'dhcpd' you can just browse to $IP_OF_GUEST and you get your Plone site.

Known issues
------------

- atm the image is depending on virtualbox guest extensions [usb], this gives you an error if you import to a machine where these are not installed, it is easy to fix on the host, but still, should we change that ?
