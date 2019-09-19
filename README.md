# fivem_uptime
Show uptime in server list for FXServer

## Download & Installation

### Using [fvm](https://github.com/qlaffont/fvm-installer)
```
fvm install --save --folder=test/uptime
```

### Using Git
```
cd resources
git clone https://gihub.com/bsimser/fivem_uptime uptime
```

### Manually
- Download https://github.com/bsimser/fivem_uptime/archive/master.zip
- Put it in the `resource` directory

## Installation
- Add this to your `server.cfg`:

```
add_ace resource.uptime command.sets allow
start uptime
```
