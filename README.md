# dogecoin-miner

A docker container for mining doge coin using your CPU

> I used `aikapool.com` for mining

#### How to run

> Go to `aikapool.com` and create an account then create a worker.

```bash
  cd dogecoin-miner
  echo """
    USERNAME=PASTE_YOUR_USERNAME.WORKER_NAME
    PASSWORD=PASTE_YOUR_WORKERS_PASSWORD
    URL=stratum+tcp://stratum.aikapool.com:7915
  """ > .env
  docker-compose up --build -d
```

# KEEP an eye on YOUR CPU

=> I AM NOT RESPONSIBLE FOR ANY DAMAGE THIS CAN CAUSE,

# Use at your own risk
