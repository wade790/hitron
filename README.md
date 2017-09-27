# hitron_snr :bar_chart:
Munin plugin that monitors SNR on Hitron CVE-30360 cable modems

## Install

* copy hitron_snr to /etc/munin/plugins
* create file /etc/munin/plugin-conf.d/hitron with this content
```
[hitron_*]
env.host 192.168.100.1
env.user admin
env.pass yourpass
```
* adjust env.host, env.user and env.pass
* restart munin

## Example

![Munin Example](https://github.com/mreymann/hitron/blob/master/example.png)
