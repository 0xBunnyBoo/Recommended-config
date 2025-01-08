# app.toml
minimum-gas-prices = "0.02uart"

pruning = "custom"
pruning-keep-recent = 362880
pruning-interval = 100
pruning-keep-every = 0

[api]
enable = true
address = "tcp://0.0.0.0:1317"

[grpc]
address = "0.0.0.0:9090"

[grpc-web]
address = "0.0.0.0:9091"

[state-sync]
snapshot-interval = 1000
snapshot-keep-recent = 10

[json-rpc]
address = "0.0.0.0:8545"
