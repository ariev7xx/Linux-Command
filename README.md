# Linux-Command
- **view cpu thermal**
```bash
watch -n 1 cat /sys/class/thermal/thermal_zone*/temp
```
- **view cpu current freq**
```bash
watch -n 1 cat /sys/devices/system/cpu/cpu*/cpufreq/cpuinfo_cur_freq
```
- **view cpu governor**
```bash
cat /sys/devices/system/cpu/cpu*/cpufreq/scaling_governor
```
- **set cpu governor**

powersave, conservative, userspace, ondemand, performance, schedutil

`apt install cpufrequtils`
```bash
cpufreq-set -g schedutil
```
