# iwdwifi

iwdwifi is a tool (use versions before the last 2 commits until bigs are fixed) governed by the Mozilla Public License V. 2.0 license. It acts like NetworkManager's nmtui (without the overhead from NetworkManager or scanning for networks), acting as a TUI menu for native iwd. Written in C using ncurses, it allows manual configuration of SSID, passphrase, MTU, DNS, BSSID, and device name. The C source code is provided in this repository. If you have any issues please tell me. Admittedly this only has a minimal networking performance boost, but a boost nevertheless and sometimes that little bit matters, hope this helps others as much as it helped me.

## Dependencies 
• libncurses-dev
• iwd

This project is licensed under the Mozilla Public License 2.0. Any modified version of my iwmenu.c file that gets distributed must remain under this license and stay open-source due to legal rights. Please see the LICENSE file or https://mozilla.org/MPL/2.0/. for the full terms. Other users are free to modify and distribute this file if they follow the MPL 2.0 licensing agreements.
