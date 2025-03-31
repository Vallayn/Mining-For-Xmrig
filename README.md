# Mining For Xmrig
Xmrig + config.json + Nicehash


I created a config.json, which I have revised from some of what I have observed. At some point understanding the ins and outs of this system. hopefully it helps those of you who are having trouble 😆


# XMRigCC

XMRigCC is a high performance, open source, cross platform RandomX, GhostRider, KawPow, CryptoNight
unified CPU/GPU miner. Official binaries are available for Windows, Linux, freebsd, macOS and Android.

[![Windows Build status](https://ci.appveyor.com/api/projects/status/l8v7cuuy320a4tpd?svg=true)](https://ci.appveyor.com/project/Bendr0id/xmrigcc)
[![Docker Pulls](https://img.shields.io/docker/pulls/bendr0id/xmrigcc.svg)](https://hub.docker.com/r/bendr0id/xmrigcc/)
[![GitHub release](https://img.shields.io/github/release/bendr0id/xmrigCC/all.svg)](https://github.com/bendr0id/xmrigCC/releases)
[![Github downloads latest](https://img.shields.io/github/downloads/bendr0id/xmrigCC/latest/total.svg)](https://github.com/bendr0id/xmrigCC/releases)
[![Github downloads total](https://img.shields.io/github/downloads/bendr0id/xmrigCC/total.svg)](https://github.com/bendr0id/xmrigCC/releases)
[![GitHub stars](https://img.shields.io/github/stars/bendr0id/xmrigCC.svg)](https://github.com/bendr0id/xmrigCC/stargazers)
[![chat on Discord](https://img.shields.io/discord/454197671528366100?logo=discord)](https://discord.gg/r3rCKTB)


![XMRigCC Logo](https://i.imgur.com/7mi0WCe.png)

### About [CC]

XMRigCC is a [XMRig](https://github.com/xmrig/xmrig) fork which adds remote control and monitoring functions to XMRigCC miners. It lets you control your miners via a Dashboard or the REST api.
XMRigCC has a "Command and Control" (CC) server part, a daemon to keep the XMRigCC miner alive and modifications to send the current status to the CC Server.
The modified version can handle commands like "update config", "start/stop mining" or "restart/shutdown/reboot" which can be send from the CC-Server Dashboard.
Assign config templates to multiple miners with a single click and let them switch configs without connecting to each of them.
Watch your miners logs with the simple remote Log viewer and monitor you miners. When the hashrate drops or one of your miners went offline you can get a notification via
PushOver or Telegram automatically so that you dont need to watch your miners all day.

Full Windows/Linux/OSx/Android compatible, and you can mix all on a single XMRigCC-Server.

## Latest integrated algos in XMRigCC:

List of all supported algos can be found [here](doc/ALGORITHMS.md)

* **Equilibria (XEQ)** RX variant (Algo: "rx/xeq")
* **Tuske** RX variant (Algo: "rx/tuske")
* **VKAX** Ghostrider variant Mike (Algo: "mike")
* **XDagger** RX variant (Algo: "rx/xdag")
* **Conceal (CCX), RYO, ...** CN variant (Algo: "cn/gpu")
* **Ghostrider (Raptoreum)** (Algo: "gr")
* **KawPow (Ravencoin)** (Algo: "kawpow")
* **Graft** RX variant (Algo: "rx/graft")
* **Yadacoin** RX variant (Algo: "rx/yada")
