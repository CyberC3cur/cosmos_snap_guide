# cosmos_snap_guide
open RPC
```
laddr = "tcp://0.0.0.0:26657"
```
make some shanges in $HOME/.project_name/config/app.toml
```
snapshot-interval = 1000
snapshot-keep-recent = 2
```
check the node status and restart it
