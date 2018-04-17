# Grafana


```
oc new-build --binary --name=grafana
oc start-build grafana --from-dir=. --follow
oc new-app grafana
oc expose service grafana
```
