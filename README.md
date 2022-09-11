influx_bridge

systemd service for taking mqtt messages and putting them into influx

sudo systemctl status mqtt_bridge


Found that default installs of influxdb and grafan tend to logg at info level and produce rather large syslog sizes.

influxdb.conf.example : influxdb example conf that turns off logging
grafana.ini.example   : grafan example conf that turns off logging


