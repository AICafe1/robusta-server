# robusta-server

* Auto-trading platform: Robusta
* Release: Server & Data
* Auto: Update data

## Linux
```sh
# Robusta Data
curl -L https://github.com/AICafe1/robusta-server/releases/latest/download/rdata-linux.tgz | tar -xz
# Robusta Server
curl -L https://github.com/AICafe1/robusta-server/releases/latest/download/robusta-linux.tgz | tar -xz
```
Cron PATH=/usr/bin:/bin

## MacOS
```sh
# Robusta Data
curl -L https://github.com/AICafe1/robusta-server/releases/latest/download/rdata-macos.tgz | tar -xz
# Robusta Server
curl -L https://github.com/AICafe1/robusta-server/releases/latest/download/robusta-macos.tgz | tar -xz
```

## Windows
```powershell
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
# Robusta Data
Invoke-WebRequest -OutFile rdata.zip https://github.com/AICafe1/robusta-server/releases/latest/download/rdata.exe.zip
Expand-Archive rdata.zip .
rm rdata.zip
# Robusta Server
Invoke-WebRequest -OutFile robusta.zip https://github.com/AICafe1/robusta-server/releases/latest/download/robusta.exe.zip
Expand-Archive robusta.zip .
rm robusta.zip
```
