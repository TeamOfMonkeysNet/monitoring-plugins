# DOSarrest Uptime

## Compile Instructions

- check_http

```bash
sudo apt install libjson-c-dev # Ubuntu 18.04
CFLAGS=$(pkg-config --cflags json-c) LDFLAGS=$(pkg-config --libs json-c) ./configure
make
```

## Deployment Instructions

Update provisioning repo with updated check binaries and use Ansible playbooks to deploy to remote servers.