#TryItOnline Stack Exchange Bot

## Docker

You can run the TIOBot under docker by running:

```shell
docker run -v ${TIOConfigPath}:/TIOBot/config jasonrivers/tiobot:latest
```

Note: The config directory and the rooms.json and config.json files should be writable by UID 1000

