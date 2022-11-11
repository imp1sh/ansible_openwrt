# Ansible Collection - imp1sh.ansible_openwrt

Install via
```
ansible-galaxy collection install imp1sh.ansible_openwrt
```

This is an Ansible collection for OpenWrt devices. It will only work if you have enough flash space available to install python which is required. Details can be found in the [documentation](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection).
It has been tested on virtualized x86 (kvm), PC Engines APU4, Edgerouter X and Deciso DEC740.
## Who is this for?
OpenWrt typically is being used in small environments but this collection is a game changer. You could run virtualized firewalls with this in cloud environments or as a hosting provider. This role is an alternative solution to what OpenWisp does. You can manage hundreds or thousands of devices centrally with Ansible.

Click the link for the [documentation.](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection)
Here is a [Youtube video](https://youtu.be/f1qrP3AagLM) I made in order to introduce it.
The old german documentation is not being updated any more, instead the english docs are now reference.

Sections:
- [Ansible OpenWrt general usage](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection)
- [Ansible OpenWrt ACME](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleAcme)
- [Ansible OpenWrt DHCP](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleDHCP)
- [Ansible OpenWrt Dropbear SSH](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleDropbear)
- [Ansible OpenWrt Firewall](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleFirewall)
- [Ansible OpenWrt Network](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleNetwork)
- [Ansible OpenWrt Packages](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/rolePackages)
- [Ansible OpenWrt Restic Backup](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleRestic)
- [Ansible OpenWrt SQM QoS](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleSQM)
- [Ansible OpenWrt Service](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleServices)
- [Ansible OpenWrt System](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleSystem)
- [Ansible OpenWrt Tinyproxy](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleTinyproxy)
- [Ansible OpenWrt Wireguard](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleWireguard)
- [Ansible OpenWrt Wireless](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleWireless)
- [Ansible OpenWrt Imagebuilder](https://wiki.junicast.de/en/junicast/docs/AnsibleOpenWrtCollection/roleImagebuilder)
