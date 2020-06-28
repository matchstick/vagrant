# vagrantwindows
vagrant setup for windows VM work.

## Install an RDP client

On Mac this would be [Microsoft Remote Desktop
10](https://itunes.apple.com/us/app/microsoft-remote-desktop/id1295203466?mt=12)

When you vagrant up should see something similar to:

`==> default: Forwarding ports...
  default: 3389 (guest) => 3389 (host) (adapter 1)
`

Then vagrant rdp should launch Remote Desktop and connect to the VM.
  * connect to 127.0.0.1:3389
  * user vagrant
  * passwd vagrant
