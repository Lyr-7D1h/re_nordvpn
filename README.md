# Nordvpn Simplified to scripts

These scripts are meant for **Arch Linux** not recommended for other use.

Syncs the openvpn files. Changes network configuration as needed and includes a small connection tool for running openvpn.

# Changes

I like transparency so I'll try to enlist all changes happening to you system when run.

## Files

- /etc/ufw/sysctl.conf
- /etc/default/ufw
- /etc/ssl/private/nordvpn.conf
- /etc/openvpn/ovpn_tcp
- /etc/openvpn/ovpn_udp

# TODO

- Proper ufw configuration
- Ufw kill switch
- Best server selector (failsafe if not exists)
- Select server based on country
- Support udp files
- See if other protocols are possible
- Finish breakdown scripts

# Notes

Would love to use wireguard but nordvpn is being a lil b\*tch (I'm very ignorant please forgive me)
