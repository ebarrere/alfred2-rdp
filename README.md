# Alfred 2 RDP Workflow

Quick-connect for iTap and MS RDP

## Usage:

* Type **rdp \<hostname/IP\>[:port]** (port defaults to 3389)
* **Enter** will open an RDP session to the host using the default system application (can be set using APP variable in script)
* Provide a "short hostname" (non-FQDN hostname) to auto-append the search suffix from `/etc/resolv.conf`

![screenshot](https://raw.github.com/ebarrere/alfred2-rdp/master/screenshots/screenshot.png)
