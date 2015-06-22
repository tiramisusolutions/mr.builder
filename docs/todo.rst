====
ToDo
====

- add hwo to 'load' supervisior to docs
- change user or build location plone/Plone is confusing
- add nice bashrc
- better password for server, maybe even user admin ?
- do we need a get_ip_script ?
- add networking to nat


Network
-------

default is now nat with forwarding pot 80, we should add also a port forward
for port 22.

there is nginx pre installed and configured, if you change network to
'dhcpd'you can just brose to $IP_OF_GUEST and you get your plone site.

Known stuff
-----------

atm the image is depending on virtualbox guest extenisions [usb], this gives you an error if you import to a machine where these are not installed, it is easy to fix on the host, but still, should we change
that ?
