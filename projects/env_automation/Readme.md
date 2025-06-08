# How to Deply

### Check Your AWS Account

```sh
aws sts get-deploy-identity
```

### Run Deploy Script
```sh
cd projects/env_automation
chmod u+x ./bin/deploy
./bin/deploy
```

> you only have to chmod the file once tomake it executable.