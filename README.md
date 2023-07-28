# can-i-update
Check if its safe to update Arch!
## Installation
Required packages:


`
git
`


`
curl
`


Install it on your system:


```
curl -O https://raw.githubusercontent.com/Schwarzeisc00l/can-i-update/main/ciu && chmod +x ciu && sudo mv ciu /usr/bin/
```

## Usage 
`ciu` to check




`ciu --vm` to see the VM specs.




## VM Specs
Minimal Arch Installation with no extra packages installed.
Bootloader: grub
Network: NetworkManager (Using wired, this project won't help with wifi.)
Drive: Ext4
Virtual Machine Specs: QEMU, 1 Core and 1024MB memory.



## What you can't check with this
`Wifi/Bluetooth`




`Any kernel other than vanilla linux`




`Any driver that doesn't come built-in the kernel.`



`Any package that isn't installed by default`



## About

Why?
`Too many broken Arch installations.`



How often do you check?
`Normally once a week. I don't know about later.`
