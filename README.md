## Mysterium-vpn-fixed-deb
Fixed deb package for debian/parrot/ubuntu users who has problem with no libappindicator3-1.

md5: 3f5bc4dad4f44e659a538e6de515c923
sha1: 5eb790dce357012100d829214f0949f2b2a5691f
sha256: 099c7c8550492af564d1a57ca7c3debdf362c55a48ddceb0f35d86429f0f5133
crc32: b4e79358

## VirusTotal
https://www.virustotal.com/gui/file/099c7c8550492af564d1a57ca7c3debdf362c55a48ddceb0f35d86429f0f5133

## Installation guide
    sudo apt install ./mysterium-fixed.deb

## Daemon wont load - fix
When your daemon isnt loading and ur net is crashed, execute that command

    sudo nano /etc/resolv.conf
    
And add 2 new lines:

    nameserver 1.1.1.1
    nameserver 1.0.0.1
    
restart mysterium and it will be fine
