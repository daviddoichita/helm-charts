### To run should

```bash
export monitoringPasscode=""
```

```bash
helm upgrade --install -n sonarqube sonarqube . --set monitoringPasscode=$MONITORING_PASSCODE
```
