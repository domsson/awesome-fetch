# awesome-fetch

A list of scripts and programs that can fetch information and print it to `stdout`. Possible use cases for such utilities:

- Check information on the CLI
- For use in custom fetch scripts
- For use in notifications
- For use in status bars

Please open an issue or send a pull request to add to the list.

# Collections

- [candies](https://github.com/domsson/candies) C programs made with status bars in mind; most of these have the option to be kept running
  - [cpu-proc](https://github.com/domsson/candies/tree/master/cpu-proc) CPU usage in %
  - [datetime](https://github.com/domsson/candies/tree/master/datetime) date and time
  - [disk-statvfs](https://github.com/domsson/candies/tree/master/disk-statvfs) disk usage in %
  - [mc-server](https://github.com/domsson/candies/tree/master/mc-server) Minecraft Server Info
  - [mem-proc](https://github.com/domsson/candies/tree/master/mem-proc) RAM usage in % via /proc/meminfo
  - [mem-sysinfo](https://github.com/domsson/candies/tree/master/mem-sysinfo) RAM usage in % via sysinfo()
  - [temp-sensors](https://github.com/domsson/candies/tree/master/temp-sensors) system temperature via libsensors
  - [twitch-chat](https://github.com/domsson/candies/tree/master/twitch-chat) Twitch chat messages (filtered)
  - [volume-pulse](https://github.com/domsson/candies/tree/master/volume-pulse) volume via libpulse
- [fetchutils](https://github.com/lptstr/fetchutils) small Shell scripts to retrieve system information; made with fetch scripts in mind
  - [disk.sh](https://github.com/lptstr/fetchutils/blob/master/src/disk.sh) disk usage
  - [editor.sh](https://github.com/lptstr/fetchutils/blob/master/src/editor.sh) get editor name
  - [mem.sh](https://github.com/lptstr/fetchutils/blob/master/src/mem.sh) RAM usage
  - [os.sh](https://github.com/lptstr/fetchutils/blob/master/src/os.sh) operating system
  - [pkgs.sh](https://github.com/lptstr/fetchutils/blob/master/src/pkgs.sh) number of packages
  - [res.sh](https://github.com/lptstr/fetchutils/blob/master/src/res.sh) screen dimensions
  - [cpu.sh](https://github.com/lptstr/fetchutils/blob/master/src/temp.sh) CPU temperature
  - [upt.sh](https://github.com/lptstr/fetchutils/blob/master/src/upt.sh) uptime
  - [wm.sh](https://github.com/lptstr/fetchutils/blob/master/src/wm.sh) window manager
- [i3blocks-contrib](https://github.com/vivien/i3blocks-contrib) mostly Shell and Python scripts; made with i3blocks in mind
  - [afs](https://github.com/vivien/i3blocks-contrib/tree/master/afs) AFS directory usage
  - [apt-upgrades](https://github.com/vivien/i3blocks-contrib/tree/master/apt-upgrades) pending aptitude upgrades
  - [aur-update](https://github.com/vivien/i3blocks-contrib/tree/master/arch-update) AUR updates
  - [backlight](https://github.com/vivien/i3blocks-contrib/tree/master/backlight) screen brightness
  - [bandwidth](https://github.com/vivien/i3blocks-contrib/tree/master/bandwidth) bandwidth information
  - [bandwidth2](https://github.com/vivien/i3blocks-contrib/tree/master/bandwidth2) bandwidth usage (written in C)
  - [bandwidth3](https://github.com/vivien/i3blocks-contrib/tree/master/bandwidth3) bandwidth usage
  - [battery-poly](https://github.com/vivien/i3blocks-contrib/tree/master/battery-poly) battery info
  - [battery](https://github.com/vivien/i3blocks-contrib/tree/master/battery) battery info
  - [battery2](https://github.com/vivien/i3blocks-contrib/tree/master/battery2) battery info
  - [batterybar](https://github.com/vivien/i3blocks-contrib/tree/master/batterybar) battery level in squares
  - [calendar](https://github.com/vivien/i3blocks-contrib/tree/master/calendar) current date and time
  - [cpu\_usage](https://github.com/vivien/i3blocks-contrib/tree/master/cpu_usage) CPU usage
  - [cpu\_usage2](https://github.com/vivien/i3blocks-contrib/tree/master/cpu_usage2) CPU usage (written in C)
  - [cpu\_util\_detailed](https://github.com/vivien/i3blocks-contrib/tree/master/cpu_util_detailed) CPU utilization
  - [disk\_io](https://github.com/vivien/i3blocks-contrib/tree/master/disk-io) disk reads/writes
  - [disk](https://github.com/vivien/i3blocks-contrib/tree/master/disk) disk usage
  - [docker](https://github.com/vivien/i3blocks-contrib/tree/master/docker) number of running Docker containers
  - [email](https://github.com/vivien/i3blocks-contrib/tree/master/email) number of new emails via IMAP
  - [essid](https://github.com/vivien/i3blocks-contrib/tree/master/essid) wifi ESSID
  - [go](https://github.com/vivien/i3blocks-contrib/tree/master/go) installed Go version
  - [gpu-load](https://github.com/vivien/i3blocks-contrib/tree/master/gpu-load) nVidia GPU load
  - [iface](https://github.com/vivien/i3blocks-contrib/tree/master/iface) network interface status
  - [kbdd\_layout](https://github.com/vivien/i3blocks-contrib/tree/master/kbdd_layout) keyboard layout via dbus and kbdd
  - [key\_layout](https://github.com/vivien/i3blocks-contrib/tree/master/key_layout) keyboard layout via setxkbmap
  - [keyindicator](https://github.com/vivien/i3blocks-contrib/tree/master/keyindicator) capslock / numlock status indicator
  - [kubernetes](https://github.com/vivien/i3blocks-contrib/tree/master/kubernetes) current Kubernetes context and namespace
  - [load\_average](https://github.com/vivien/i3blocks-contrib/tree/master/load_average) system load average
  - [mediaplayer](https://github.com/vivien/i3blocks-contrib/tree/master/mediaplayer) generic media player status
  - [memory](https://github.com/vivien/i3blocks-contrib/tree/master/memory) RAM usage
  - [nm-vpn](https://github.com/vivien/i3blocks-contrib/tree/master/nm-vpn) VPN status/name via nmcli
  - [openvpn](https://github.com/vivien/i3blocks-contrib/tree/master/openvpn) OpenVPN
  - [ssid](https://github.com/vivien/i3blocks-contrib/tree/master/ssid) wifi SSID
  - [sway-focusedwindow](https://github.com/vivien/i3blocks-contrib/tree/master/sway-focusedwindow) Sway WM focused window title
  - [systemd\_unit](https://github.com/vivien/i3blocks-contrib/tree/master/systemd_unit) systemd unit status
  - [tahoe-lafs](https://github.com/vivien/i3blocks-contrib/tree/master/tahoe-lafs) tahoe-lafs grid status
  - [temperature](https://github.com/vivien/i3blocks-contrib/tree/master/temperature) system temperatures
  - [time](https://github.com/vivien/i3blocks-contrib/tree/master/time) current time
  - [usb](https://github.com/vivien/i3blocks-contrib/tree/master/usb) USB device info
  - [volume-pulseaudio](https://github.com/vivien/i3blocks-contrib/tree/master/volume-pulseaudio) system volume and default playback device
  - [volume](https://github.com/vivien/i3blocks-contrib/tree/master/volume) system volume
  - [wifi](https://github.com/vivien/i3blocks-contrib/tree/master/wifi) wifi connection strength
  - [wlan-dbm](https://github.com/vivien/i3blocks-contrib/tree/master/wlan-dbm) wifi interface link quality in dBm or percent
  - [xkb\_layout](https://github.com/vivien/i3blocks-contrib/tree/master/xkb_layout) keyboard layout
- [polybar-scripts](https://github.com/polybar/polybar-scripts) Shell and Python scripts; written with polybar in mind
  - todo
- [slstatus](https://github.com/drkhsh/slstatus) status monitor, written in C; with status bars in mind; individual components could be extracted
  - todo

## Invidiual projects

- [xtmon](https://github.com/vimist/xtmon) X window title monitoring (C)
- [pavolmon](https://github.com/everard/pavolmon) PulseAudio volume monitoring (C)
- [xkblayout-state](https://github.com/nonpop/xkblayout-state) XKB keyboard layout (C++)
- [light](https://github.com/haikarainen/light) get and set backlights (C)
- [brightnessctl](https://github.com/Hummer12007/brightnessctl) get and set device brightness (C)
- [ansiweather](https://github.com/fcambus/ansiweather) Shell script for weather conditions

## Services

See [awesome-console-services](https://github.com/chubin/awesome-console-services)
