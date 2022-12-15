Create Systemd Linux Service
```sh
sudo vim /etc/systemd/system/my-server.service
```

```sh
sudo systemctl start my-server
```

```sh
sudo systemctl enable my-server
```

```sh
sudo systemctl status my-server
```

```sh
journalctl -u my-server -f --no-pager
```

```sh
curl localhost:8080/hello
```