# tcp-port-wait
Wait container is accepting TCP connections.

## Example

```
echo "Waiting ip:port connecting"

# FIXME： timeout is not included
sh tcp-port-wait.sh 127.0.0.1 5432

echo "Done tcp-port-wait"
```
