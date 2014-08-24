#Dokku in Docker in Docker

Start container like so:

```bash
docker run -d -t -i -e VHOSTNAME=example.org -e USERNAME=progrium -e PUBKEY='your ssh pubkey here' --privileged -p 22 -p 80 --name dokku dindind
```

Attach to the container to get a shell.
