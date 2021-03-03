SystemD unit service script
---------------------------

```shell
sudo cp prometheus.service /etc/systemd/system/prometheus.service
sudo systemctl enable prometheus
sudo systemctl start prometheus

sudo cp sunpower.pvs.exporter.service /etc/systemd/system/sunpower.pvs.exporter.service
sudo systemctl enable sunpower.pvs.exporter.service
sudo systemctl start sunpower.pvs.exporter.service
```
