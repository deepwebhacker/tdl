## tdl chat export

export messages from (protected) chat for download

```
tdl chat export [flags]
```

### Options

```
  -c, --chat string     chat id or domain
      --from int        starting message
  -h, --help            help for export
      --msg             the format for from&to is message id
  -o, --output string   output JSON file path (default "tdl-export.json")
      --time            the format for from&to is timestamp
      --to int          ending message, default value is NOW/LATEST
```

### Options inherited from parent commands

```
      --debug          enable debug mode
  -l, --limit int      max number of concurrent tasks (default 2)
  -n, --ns string      namespace for Telegram session
      --ntp string     ntp server host, if not set, use system time
      --proxy string   proxy address, only socks5 is supported, format: protocol://username:password@host:port
  -s, --size int       part size for transfer, max is 512*1024 (default 131072)
  -t, --threads int    max threads for transfer one item (default 4)
```

### SEE ALSO

* [tdl chat](tdl_chat.md)	 - A set of chat tools

