## Send signals to processes

```bash
    kill 1234       // Kill a process gracefully (default)
    kill -9 1234    // Force kill a process
    pkill firefox   // Kill a process by name
```

| Signal    | Number | Description                                        |
| --------- | ------ | -------------------------------------------------- |
| `SIGTERM` | `15`   | Graceful stop (default)                            |
| `SIGKILL` | `9`    | Forceful termination (cannot be caught or ignored) |
| `SIGHUP`  | `1`    | Hangup (often causes reload)                       |
| `SIGINT`  | `2`    | Interrupt (same as Ctrl+C)                         |
| `SIGSTOP` | `19`   | Pause the process                                  |
| `SIGCONT` | `18`   | Continue a stopped process                         |
