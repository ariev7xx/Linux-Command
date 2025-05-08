# Linux-Command
**view cpu thermal**
```bash
watch -n 1 cat /sys/class/thermal/thermal_zone*/temp
```
**view cpu current freq**
```bash
watch -n 1 cat /sys/devices/system/cpu/cpu*/cpufreq/cpuinfo_cur_freq
```
**view cpu governor**
```bash
cat /sys/devices/system/cpu/cpu*/cpufreq/scaling_governor
```
