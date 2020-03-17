Self hosted media center

# How to run

Clone the repository and run:

```bash
docker-compose up -d
```

The Emby media center should be accessible in `http://localhost/emby`

The torrent manager should be accessible in `http://localhost/torrents`

# Media location

The torrent download location is set to the `media` folder, in the Emby server you should point your library to the mapped directory `/home/media`

# Default port

To override the default http port, the REV_PORT variable can be set to the desired service port