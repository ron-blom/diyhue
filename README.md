# diyhue
This project is part of my [homeserver](https://github.com/ron-blom/homeserver) project and will deploy diyHue with it's own ip address on my homeserver. Change address in values.yaml to fit your own network.

IP address used:
```
192.168.110.7
```

persistend storage:
```
/opt/hue-emulator/export
```

Images used in this project:
```
https://hub.docker.com/r/diyhue/core
```

### Deploy 

helm upgrade --install diyhue-chart ./diyhue-chart
