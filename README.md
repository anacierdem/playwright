# Playwright devcontainer

Very basic Playwright configuration for running it in devcontainer.

### Run tests:

```shell
npx playwright test
```

### Run a project in headed mode:

```shell
npx playwright test --headed
```

### Run UI mode:

```shell
npx playwright test --ui
```

If you are using an incompatible environment (see https://github.com/microsoft/playwright/issues/36958), you can simply run it on network;

```shell
npx playwright test --ui --ui-host 0.0.0.0 or --ui-port 9000
```
