# Console Snippets

[![Version](https://vsmarketplacebadge.apphb.com/version/deinsoftware.console-snippets.svg?color=blue&label=version)](https://marketplace.visualstudio.com/items?itemName=deinsoftware.console-snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/deinsoftware.console-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=deinsoftware.console-snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/deinsoftware.console-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=deinsoftware.console-snippets)
[![license](https://img.shields.io/github/license/deinsoftware/vscode-console-snippets)](LICENSE.md)
[![Open in VS Code](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://open.vscode.dev/deinsoftware/vscode-console-snippets)

![Console](https://raw.githubusercontent.com/deinsoftware/vscode-console-snippets/main/.github/social/preview.png 'Console Snippets')

The quick and easy way to create and use Console with [VS Code](https://code.visualstudio.com/).

## Menu

- [Installation](#installation)
  - [Quick Launch](#quick-launch)
  - [Extension Manager](#extension-manager)
  - [Marketplace](#marketplace)
- [Supported Languages](#supported-languages)
- [Snippets](#snippets)
- [About](#about)

---

## Installation

### Quick Launch

Open the quick launch with <kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>P</kbd> (Win/Linux) or <kbd>cmd</kbd>+<kbd>shift</kbd>+<kbd>P</kbd> (macOS).

Paste the following command and press `Enter`:

```shell
ext install deinsoftware.console-snippets
```

### Extension Manager

Open the extension manager with <kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>X</kbd> (Win/Linux) or <kbd>cmd</kbd>+<kbd>shift</kbd>+<kbd>X</kbd> (macOS), search for `Console Snippets` and click on `[Install]` button.

### Marketplace

[Console Snippets](https://marketplace.visualstudio.com/items?itemName=deinsoftware.console-snippets)

⇧ [Back to menu](#menu)

---

## Supported Languages

| Language         | Extension |
| ---------------- | --------- |
| JavaScript       | `.js`     |
| TypeScript       | `.ts`     |
| CSS              | `.css`    |

⇧ [Back to menu](#menu)

---

## Snippets

Below is a list of all available snippets and the triggers of each one. The **→** means the `TAB` key and `█` the final cursor position.

### JS/TS

| Trigger | Description                                                                                        | Result JS/TS                    |
| ------: | -------------------------------------------------------------------------------------------------- | ------------------------------- |
|  `dbg→` | [debugger](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/debugger)  | `debugger`                      |
|   `cl→` | [log](https://developer.mozilla.org/en-US/docs/Web/API/Console/log)                                | `console.log(█)`                |
|  `clm→` |   log with message                                                                                 | `console.log('message:', █)`    |
|  `cld→` |   log with destructuring                                                                           | `console.log({█})`              |
|   `cd→` | [debug](https://developer.mozilla.org/en-US/docs/Web/API/Console/debug)                            | `console.debug(█)`              |
|  `cdm→` |   debug with message                                                                               | `console.debug('message:', █)`  |
|  `cdd→` |   debug with destructuring                                                                         | `console.debug({█})`            |
|   `ci→` | [info](https://developer.mozilla.org/en-US/docs/Web/API/Console/info)                              | `console.info(█)`               |
|  `cim→` |   info with message                                                                                | `console.info('message:', █)`   |
|  `cid→` |   info with destructuring                                                                          | `console.info({█})`             |
|   `ce→` | [error](https://developer.mozilla.org/en-US/docs/Web/API/Console/error)                            | `console.error(█)`              |
|  `cem→` |   error with message                                                                               | `console.error('message:', █)`  |
|  `ced→` |   error with destructuring                                                                         | `console.error({█})`            |
|   `cw→` | [warn](https://developer.mozilla.org/en-US/docs/Web/API/Console/warn)                              | `console.warn(█)`               |
|  `cwm→` |   warn with message                                                                                | `console.warn('message:', █)`   |
|  `cwd→` |   warn with destructuring                                                                          | `console.warn({█})`             |
|   `ct→` | [table](https://developer.mozilla.org/en-US/docs/Web/API/Console/table)                            | `console.table(█)`              |
|   `ca→` | [assert](https://developer.mozilla.org/en-US/docs/Web/API/Console/assert)                          | `console.assert(assertion, █)`  |
|  `cdr→` | [dir](https://developer.mozilla.org/en-US/docs/Web/API/Console/dir)                                | `console.dir(█)`                |
|  `ctr→` | [trace](https://developer.mozilla.org/en-US/docs/Web/API/Console/trace)                            | `console.trace()`               |
|  `cts→` | [time start](https://developer.mozilla.org/en-US/docs/Web/API/Console/time)                        | `console.time(█)`               |
|  `ctl→` | [time log](https://developer.mozilla.org/en-US/docs/Web/API/console/timeLog)                       | `console.timeLog(█)`            |
|  `cte→` | [time end](https://developer.mozilla.org/en-US/docs/Web/API/console/timeEnd)                       | `console.timeEnd(█)`            |
|  `ctg→` | [time group](https://developer.mozilla.org/en-US/docs/Web/API/Console/time)                        | <code>console.time()<br/>█<br/>console.timeEnd()</code> |
|   `cc→` | [count](https://developer.mozilla.org/en-US/docs/Web/API/Console/count)                            | `console.count(label█)`         |
|  `ccr→` | [count reset](https://developer.mozilla.org/en-US/docs/Web/API/Console/countReset)                 | `console.countReset(label█)`    |
|  `cgs→` | [group start](https://developer.mozilla.org/en-US/docs/Web/API/Console/group)                      | `console.group()`               |
|  `cge→` | [group end](https://developer.mozilla.org/en-US/docs/Web/API/console/groupEnd)                     | `console.groupEnd()`            |
|  `cgg→` | [time group](https://developer.mozilla.org/en-US/docs/Web/API/Console/time)                        | <code>console.group()<br/>█<br/>console.groupEnd()</code> |
|  `clr→` | [clear](https://developer.mozilla.org/en-US/docs/Web/API/Console/clear)                            | `console.clear(█)`              |

### CSS

| Trigger | Description                     | Result CSS                                   |
| ------: | ------------------------------- | -------------------------------------------- |
|   `cb→` | background                      | `background: rgb(0 100 0 / 0.1) !important;` |
|   `co→` | outline                         | `outline: 1px solid limegreen !important;`   |

⇧ [Back to menu](#menu)

---

## About

### Built With

- [VS Code](https://code.visualstudio.com/) - Code editing redefined.
- [Figma](https://www.figma.com/) - The collaborative interface design tool.

### Sources

- [Debug CSS with background and outlines](https://codepen.io/kevinpowell/pen/XWZBwWz)
- [Box Model](https://codepen.io/carolineartz/pen/ogVXZj)

### Contributing

Please read [CONTRIBUTING](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [Console Snippets](https://github.com/deinsoftware/vscode-console-snippets/tags) on GitHub.

### Authors

- **Camilo Martinez** [[Equiman](http://github.com/equiman)]

See also the list of [contributors](https://github.com/deinsoftware/vscode-console-snippets/contributors) who participated in this project.

### Sponsors

If this project helps you, consider buying me a cup of coffee.

[![paypal](https://img.shields.io/badge/-PayPal-gray?style=flat&labelColor=00457C&logo=paypal&logoColor=white&link=https://paypal.me/equiman/3)](https://paypal.me/equiman/3)
[![ko-fi](https://img.shields.io/badge/-Ko–Fi-gray?style=flat&labelColor=fd444a&logo=ko-fi&logoColor=white&link=https://ko-fi.com/equiman)](https://ko-fi.com/equiman)

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

⇧ [Back to menu](#menu)
