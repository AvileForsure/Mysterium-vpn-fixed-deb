## Mysterium-vpn-fixed-deb
Fixed deb package for debian/parrot/ubuntu users who has problem with no libappindicator3-1.

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
