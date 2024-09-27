# @podium/semantic-release-config

This is a [semantic-release](https://github.com/semantic-release/semantic-release) config to publish Podium modules meant for internal use in the [podium-lib organisation](https://github.com/podium-lib).

## Plugins

This shareable configuration uses the following plugins:

- [`@semantic-release/commit-analyzer`](https://github.com/semantic-release/commit-analyzer)
- [`@semantic-release/release-notes-generator`](https://github.com/semantic-release/release-notes-generator)
- [`@semantic-release/changelog`](https://github.com/semantic-release/changelog)
- [`@semantic-release/npm`](https://github.com/semantic-release/npm)
- [`@semantic-release/github`](https://github.com/semantic-release/github)
- [`@semantic-release/git`](https://github.com/semantic-release/git)

## Install

```bash
npm install --save-dev semantic-release @podium/semantic-release-config
```

## Usage

In the [semantic-release configuration file](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#configuration):

```js
export default {
	extends: "@podium/semantic-release-config",
};
```
