# robusta-server

* Auto-trading platform: Robusta
* Release: Server & Data
* Auto: Update data

## Linux
```sh
curl -L https://github.com/AICafe1/robusta-server/releases/latest/download/robusta-linux.tgz | tar -xz
```
```sh
curl -L https://github.com/AICafe1/robusta-server/releases/latest/download/robusta-linux.tar.zst | tar --zstd -x
```
Cron PATH=/usr/bin:/bin

## MacOS
```sh
curl -L https://github.com/AICafe1/robusta-server/releases/latest/download/robusta-macos.tgz | tar -xz
```

## Windows
```powershell
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
Invoke-WebRequest -OutFile robusta.zip https://github.com/AICafe1/robusta-server/releases/latest/download/robusta.exe.zip
Expand-Archive robusta.zip .
rm robusta.zip
```
