## How to Run

``` bash
make # requires make and g++ with C++14 support installed
```

### To start the server:

``` bash
./server
# or ./server PORT BACKLOG
# like: ./server 4000
```

Defaults:
- `PORT`: `8000`
- `BACKLOG`: `5`

### To start a client:

``` bash
./client
# or ./client HOST PORT
```

Defaults:
- `HOST`: `127.0.0.1`
- `PORT`: `8000`


You can get the `HOST` for your server through `ifconfig` command.
