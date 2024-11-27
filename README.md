# Holograms

Holograms is a [SerenityJS](https://github.com/SerenityJS/serenity/tree/rc-1) plugin to add a dynamic floating text

---

The configuration is located in /plugins/Holograms/config.yml

This is the default configuration with descriptions:
```yaml
# How much space there should be between the lines of holograms.
space-between-lines: 0.02

# The maximum range in blocks to render holograms for players.
holograms-view-range: 48

# How frequently these should placeholders be updated.
refresh-seconds: 3

# Used to display various information in external servers
# such as its status or MOTD.
pinger:
    enabled: true
    servers:
        - "hub: 127.0.0.1:25565"
        - "survival: 127.0.0.1:25566"
        - "minigames: 127.0.0.1:25567"

    # Timeout in milliseconds before assuming a server is offline.
    timeout: 500

    # The MOTD to display for offline servers.
    offline-motd: "&cOffline, couldn't get the MOTD."

    # The text to display for online and offline servers.
    status:
      online: "&aOnline"
      offline: "&cOffline"

    # Remove the leading and trailing whitespace from the MOTD of servers.
    motd-remove-leading-trailing-spaces: true

```

Veiw Placeholders [Here](https://github.com/Nathan93705/Holograms/blob/main/PlaceHolders.md)
Veiw Commands [Here](https://github.com/Nathan93705/Holograms/blob/main/Commands.md)