munin-tcpportstat
=============

TCP port status count plugin for munin

# Usage

tcpportstat_ => /usr/share/munin/plugins/
chmod +x /usr/share/munin/plugins/tcpportstat_

ln -s /usr/share/munin/plugins/tcpportstat_ /etc/munin/plugins/tcpportstat_%PORT%

ex.)
ln -s /usr/share/munin/plugins/tcpportstat_ /etc/munin/plugins/tcpportstat_80
Above for Port 80(HTTP)