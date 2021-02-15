# QA Testing Sample (dpm-qa-testing-sample)

A Quasar Framework app

## Install required tools
```bash
# Install Node.js LTS
curl -sL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt-get install -y nodejs

# Install YARN
sudo npm install -g yarn

# Install Quasar CLI
yarn global add @quasar/cli
```

## Install the dependencies
```bash
yarn
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```

### Lint the files
```bash
yarn run lint
```

### Build the app for production
```bash
quasar build
```

### Run the E2E Cypress tests
### In the interactive testrunner
```bash
quasar test --e2e cypress-open
```
### In the command line testrunner
```bash
quasar test --e2e cypress-run
```

### Customize the configuration
See [Configuring quasar.conf.js](https://quasar.dev/quasar-cli/quasar-conf-js).
