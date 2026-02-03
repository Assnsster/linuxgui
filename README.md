# LinuxGUI
## RUN
```bash
docker run --name linuxguiii -p 0.0.0.0:3389:3389 -it ductris/linuxgui:latest
```
### RUN Again ( The old data is still saved )
```bash
docker start linuxguiii
```
## CONNECT
after run then go port 3389 (RDP), credentials is

User: `linux`

Pass: `linuxgui`
