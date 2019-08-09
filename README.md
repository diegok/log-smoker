# log-smoker

this is a journalctl web viewer and realtime websocket based API. I did it to deploy on our centralized journal node to be able to filter logs in real time and attach our automation software to it.

## How to use it

To run it you need perl 5.22 or up and Mojolicious. Then, you just edit the `log-smoker.conf` file to the logs you want to be streamed and then run:

```bash
./log-smoker daemon
```

