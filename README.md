# Matterwiki configuration container

Docker image that puts configuration for Matterwiki on a volume at
`/usr/local/etc/matterwiki` via [confd](https://github.com/kelseyhightower/confd).

For use with [Rancher](http://rancher.com/), because configuration files use
Rancher's [metadata service](http://docs.rancher.com/rancher/rancher-services/metadata-service/).

Based on [`weahead/conf`](https://github.com/weahead/docker-conf) that allows
local development without Rancher.


## License

[X11](LICENSE)
