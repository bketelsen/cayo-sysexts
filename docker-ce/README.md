# docker-ce

Docker Engine from [community repos](https://docs.docker.com/engine/install/centos/).

## How to use

- Install the sysext
- Create the `docker` group:
  ```
  $ sudo groupadd --system docker
  ```
- Restart the socket:
  ```
  $ sudo systemctl restart docker.socket
  ```

## Compatibility

This sysext should be compatible with all Cayo 10.
