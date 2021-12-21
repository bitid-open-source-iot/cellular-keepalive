```bash
    sudo cp cellular-keepalive /usr/sbin/cellular-keepalive
    sudo cp cellular-keepalive.service /etc/systemd/system/cellular-keepalive.service
    sudo chmod +x /usr/sbin/cellular-keepalive
    sudo systemctl enable cellular-keepalive
    sudo systemctl start cellular-keepalive
```