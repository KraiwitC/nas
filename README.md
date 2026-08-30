# Home NAS

## Access Links

- Cockpit: https://nas.local:9090
- Homer: http://nas.local
- Jellyfin: http://nas.local:8096
- qBittorrent: http://nas.local:8080
- OpenSpeedTest: http://nas.local:3000
- SMB Share: Network Discover

## Directory Structure

- ~/nas/docker-compose.yml
- ~/nas-data/ (jellyfin, qbittorrent, homer)
- /mnt/... (media drive)

## Config files:

- Service: /etc/systemd/system/daily-shutdown.service
- Timer: /etc/systemd/system/daily-shutdown.timer
- WOL: /etc/systemd/system/wol.service
