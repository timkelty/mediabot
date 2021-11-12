# mediabot

See [HTPC Docker Standup](https://gitlab.com/phikai/htpc-docker-standup) for documentation.

/etc/auto.master

```
/nfs   /etc/auto.nfs
```

/etc/auto.nfs

```
mediabot -fstype=nfs4 lwaxana.local:/volume1/mediabot
```