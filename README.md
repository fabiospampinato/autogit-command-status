# Autogit Command - Status

A command for showing the status of repositories.

## Install

```sh
npm install --save autogit-command-status
```

## Usage

#### Configuration

Add this command to your configuration:

```js
const status = require ( 'autogit-command-status' );

module.exports = {
  commands: {
    status
  }
}
```

#### CLI

Call it from the CLI with:

```sh
autogit status
autogit status --include '**/js-*'
```

## License

MIT © Fabio Spampinato
