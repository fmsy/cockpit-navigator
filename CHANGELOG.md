## Cockpit Navigator 0.5.9-1

* Disallow downloading files of size 0 to avoid Cockpit bug where fsread never returns.
* Overhaul copying/moving to use built in functions instead of rsync, speeding up moving files in the same fs.