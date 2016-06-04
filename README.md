# How to Use

## Build

```docker build -t duplicator .```

## Run

```docker run -d --name duplicator -e INTERFACE=0.0.0.0 -e PORT=80 -e FORWARD=192.168.0.100:8080 -e DUPLICATE=192.168.0.101:80 -p 80:80 duplicator```

