### To install this chart you should

```bash
export MONITORING_PASSCODE=""
```

```bash
helm upgrade --install --create-namespace -n sonarqube sonarqube . --set monitoringPasscode=$MONITORING_PASSCODE
```
