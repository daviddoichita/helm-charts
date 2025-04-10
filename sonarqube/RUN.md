### To install this chart you should

```bash
export monitoringPasscode=""
```

```bash
helm upgrade --install -n sonarqube sonarqube . --set monitoringPasscode=$MONITORING_PASSCODE
```
