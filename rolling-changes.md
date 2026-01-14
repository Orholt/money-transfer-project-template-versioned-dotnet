# Deployment preview
```sh
temporal worker deployment describe --name="money-transfer"
```

# Deployment version update
```sh
temporal worker deployment set-current-version --deployment-name "money-transfer" --build-id "1.0"
```

# Checking the changes
```sh
temporal worker deployment describe --name="money-transfer"
```

# Describing workflow
```sh
temporal workflow describe -w $WORKFLOW-ID
```
