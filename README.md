# Neo10's pipa-armtix pacman repo
Repository containing packages for Artix Linux on Xiaomi Pad 6

## How to add 
Copy & Paste

```bash
cat <<EOF | tee -a /etc/pacman.conf
[pipa-armtix]
SigLevel = Optional
Server = https://neo10e.github.io/pipa-armtix/repo/
EOF
```
This will add the repository to `/etc/pacman.conf`

Run `pacman -Sy` with root privileges to update repo
