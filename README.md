# That-Was-Easy

This is a rather silly and useless container I created to replace the old school easy button.

## Examples:

### docker run

docker run wk0127/easy

### docker-compose
```
  version: '3.3'

  services:
    easy:
      image: wk0127/easy
      container_name: easy
      restart: unless-stopped
```
