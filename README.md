# Windows

```ps1
PowerShell -NoProfile -ExecutionPolicy unrestricted -Command "[Net.ServicePointManager]::SecurityProtocol = 'Tls12'; iex ((new-object net.webclient).DownloadString('https://github.com/LunaStream/LuviBinary/raw/main/get-lit.ps1'))"
```

# Linux / MacOS
```
curl -L https://github.com/LunaStream/LuviBinary/raw/main/get-lit.sh | sh
```
