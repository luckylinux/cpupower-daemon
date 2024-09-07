# cpupower-daemon
Systemd Daemon + Config File which are not (anymore ?) available on Debian/Ubuntu

# Setup
Run the Installer:
```
./setup.sh
```

# Manual Commands
Set the CPU Governor to `powersave`:
```
cpupower frequency-set --governor powersav
```

# Monitor Power States
Install `powertop` Tool:
```
apt-get install powertop
```


# References
- https://askubuntu.com/questions/1102311/cpu-frequency-too-high-even-with-powersave-governor
