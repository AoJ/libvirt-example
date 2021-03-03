Docker
=========


Logs
------------
All logs are rotate, old logs are gzipped, see templates for logrotate configuration

- `/var/log/docker/daemon.log` - logs from docker daemon
- `/var/log/docker/container.log` - logs from all other docker containers