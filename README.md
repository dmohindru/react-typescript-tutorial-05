# CLI
Enable Typescript support
```shell
npx tsc --init
```
Library used
- commander

# Local API
Enable Typescript support
```shell
npx tsc --init
```

# Local Client

# Lerna commands
Link packages with each other
```shell
lerna add local-api --scope=cli
```

Parallel run all packages
```shell
npm run start
```

Publish package
```shell
lerna publish --no-push
```

Install all dependencies of sub packages
```shell
lerna bootstrap
```

