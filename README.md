# Emoji Picker Plugin for Flex UI 2.x

## About the project

The Emoji Picker was built using [Twilio Paste](https://paste.twilio.design/). This means that it will blend in with Flex UI styling and look the part when Flex UI is in dark mode. For customizing styling please refer to the Paste [design tokens](https://paste.twilio.design/tokens/list).

To add/remove emojis from the rendered list, simply modify the `src/emojis.json` file. If adding an emoji, please make sure to assign it a category which must be one of.

## Setup

Clone the repository and enter the main directory:

```bash
cd emoji-picker-2.x-plugin
```

Make sure you have [Node.js](https://nodejs.org) as well as [`npm`](https://npmjs.com). We support Node >= 10.12 (and recommend the _even_ versions of Node). Afterwards, install the dependencies by running:

```bash
# If you use npm
npm install
```

Next, please install the [Twilio CLI](https://www.twilio.com/docs/twilio-cli/quickstart) by running:

```bash
brew tap twilio/brew && brew install twilio
```

Finally, install the [Flex Plugin extension](https://github.com/twilio-labs/plugin-flex/tree/v1-beta) for the Twilio CLI:

```bash
twilio plugins:install @twilio-labs/plugin-flex@beta
```

To run the plugin locally (for testing purposes) run:

```bash
twilio flex:plugins:start
```

To deploy the plugin run:

```bash
twilio flex:plugins:deploy --changelog "WRITE YOUR CHANGELOG HERE"
```

For further details on Flex Plugins refer to our documentation on the [Twilio Docs](https://www.twilio.com/docs/flex/developer/plugins/cli) page.

