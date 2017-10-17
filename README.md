# Linux Administration Helper

Collection of bash command line utilities to help with monitoring or diagnosing problems with a linux server.

Also knows some Plesk and cPanel specific metrics as well.

## Installation

```
git clone https://github.com/Namesonic/pAdmin
sh ./ns --install
```

Installs **lah** to the ~/bin/lah folder and appends your session path in ~/.bashrc

## Usage

`lah --install` installs the binary and sets environment path.

`lah` list installed modules

`lah --help` shows this help screen

`lah --info` shows detected environment and application settings

`lah [command]` runs the specified command modules installed

## Commands

### Apache Commands

`lah access_logs`

Tails the http access logs on a broad scale.

`lah atop`

Show a "top" style view of apache usage

`lah weblog`

No idea.

`lah topswap`

Show top processes that are swapping

### Firewall Commands

`banip [ip]`

Ban the specified IP address

`unbanip [ip]`

Unban the specified IP address

### System Commands

`iotest`

Test the I/O throughput

`last_mod`

Show the last modified files recursively from the current directory.

`netstat_all`

Show a combination of network interface usage statistics.
