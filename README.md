# Playwright devcontainer

Very basic Playwright configuration for running it in devcontainer. Only linux is supported currently.

### Run tests:

```shell
npm run test
```

### Run a project in headed mode:

```shell
npm run test -- --headed
```

### Run UI mode:

```shell
npm run test -- --ui-host 0.0.0.0 --ui-port 9000
```
