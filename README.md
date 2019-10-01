# Geth prometheus metrics

Collect and visualize [Ethereum](https://github.com/ethereum/go-ethereum) / [Quorum](https://github.com/jpmorganchase/quorum) metrics with Prometheus and Grafana.

## Demo

#### Step 1

Install Docker on Mac.

#### Step 2

Start `geth` with `--metrics --metrics.expensive --pprof --pprofaddr=0.0.0.0` flags.

#### Step 3

```bash
> docker-compose up -d
```

Open [localhost:3000](http://localhost:3000) (admin:admin) to explore the Grafana metrics dashboard.

## Dashboard

Import `default.json` dashboard template to Grafana.

![Grafana](grafana.png)
