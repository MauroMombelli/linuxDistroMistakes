# linuxDistroMistakes
A list of stuff even the most user distro get wrong.

To let the year of gnu/Linux distro on desktop (before desktop disappear!) distro has a series of mistakes still have to be iron out.

# Permission Madness

- by default an user does not have access to serial port. Really want to know the reasoning for this.
- if you change user group/permission, you have to logout and login in
- we need an "app firewall" similar to Android, in particular "Privacy Guard". SELinux is too complex, and Flatpack/Snappy does not give an easy way to check/change app permission
- for some reason by default many distro let user look at other user home folder. WRONG.

# Wallet by default

- wallet like kwallet, bitwarden, keepass, should be enabled by default and integrated with all software, ESPECIALLY browser and HW keys.

# Encryption by default

- maybe Ubuntu get this right with encrypted user parition
