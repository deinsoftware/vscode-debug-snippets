# Debug Snippets

[![Version](https://vsmarketplacebadge.apphb.com/version/deinsoftware.debug-snippets.svg?color=blue&label=version)](https://marketplace.visualstudio.com/items?itemName=deinsoftware.debug-snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/deinsoftware.debug-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=deinsoftware.debug-snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/deinsoftware.debug-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=deinsoftware.debug-snippets)
[![license](https://img.shields.io/github/license/deinsoftware/vscode-debug-snippets)](LICENSE.md)
[![Open in VS Code](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://open.vscode.dev/deinsoftware/vscode-debug-snippets)

![Debug](https://raw.githubusercontent.com/deinsoftware/vscode-debug-snippets/main/.github/social/preview.png 'Debug Snippets')

The quick and easy way to debug your code and styles with [VS Code](https://code.visualstudio.com/).

## Menu

- [Installation](#installation)
  - [Quick Launch](#quick-launch)
  - [Extension Manager](#extension-manager)
  - [Marketplace](#marketplace)
- [Supported Languages](#supported-languages)
- [Snippets](#snippets)
  - [Code](#code)
  - [Styles](#styles)
- [About](#about)

---

## Installation

### Quick Launch

Open the quick launch with <kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>P</kbd> (Win/Linux) or <kbd>cmd</kbd>+<kbd>shift</kbd>+<kbd>P</kbd> (macOS).

Paste the following command and press `Enter`:

```shell
ext install deinsoftware.debug-snippets
```

### Extension Manager

Open the extension manager with <kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>X</kbd> (Win/Linux) or <kbd>cmd</kbd>+<kbd>shift</kbd>+<kbd>X</kbd> (macOS), search for `Debug Snippets` and click on `[Install]` button.

### Marketplace

[Debug Snippets](https://marketplace.visualstudio.com/items?itemName=deinsoftware.debug-snippets)

⇧ [Back to menu](#menu)

---

## Supported Languages

| Language         | Extension |
| ---------------- | --------- |
| JavaScript       | `.js`     |
| TypeScript       | `.ts`     |
| CSS              | `.css`    |
| SCSS             | `.scss`   |

⇧ [Back to menu](#menu)

---

## Snippets

Below is a list of all available snippets and the triggers of each one. The **→** means the `TAB` key and `█` the final cursor position.

### Code

| Trigger | Description                                                                                        | Result JS/TS                                                        |
| ------: | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
|  `dbg→` | [debugger](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/debugger)  | `debugger█`                                                         |
|   `cl→` | [log](https://developer.mozilla.org/en-US/docs/Web/API/Console/log)                                | `console.log(name)█`                                                |
|  `clm→` |   log with message                                                                                 | `console.log('name:', name)█`                                        |
|  `cld→` |   log with destructuring                                                                           | `console.log({name})█`                                              |
|  `clj→` |   log with json                                                                                    | `console.log('obj', JSON.stringify(obj, null, 2))█`                 |
|   `cd→` | [debug](https://developer.mozilla.org/en-US/docs/Web/API/Console/debug)                            | `console.debug(name)█`                                              |
|  `cdm→` |   debug with message                                                                               | `console.debug('name:', name)█`                                     |
|  `cdd→` |   debug with destructuring                                                                         | `console.debug({name})█`                                            |
|  `cdj→` |   debug with json                                                                                  | `console.debug('obj', JSON.stringify(obj, null, 2))█`               |
|   `ci→` | [info](https://developer.mozilla.org/en-US/docs/Web/API/Console/info)                              | `console.info(name)█`                                               |
|  `cim→` |   info with message                                                                                | `console.info('name:', name)█`                                      |
|  `cid→` |   info with destructuring                                                                          | `console.info({name})`                                              |
|  `cij→` |   info with json                                                                                   | `console.info('obj', JSON.stringify(obj, null, 2))█`                |
|   `ce→` | [error](https://developer.mozilla.org/en-US/docs/Web/API/Console/error)                            | `console.error(name)█`                                              |
|  `cem→` |   error with message                                                                               | `console.error('name:', name)█`                                     |
|  `ced→` |   error with destructuring                                                                         | `console.error({name})█`                                            |
|  `cej→` |   info with json                                                                                   | `console.error('obj', JSON.stringify(obj, null, 2))█`               |
|   `cw→` | [warn](https://developer.mozilla.org/en-US/docs/Web/API/Console/warn)                              | `console.warn(name)█`                                               |
|  `cwm→` |   warn with message                                                                                | `console.warn('name:', name)█`                                      |
|  `cwd→` |   warn with destructuring                                                                          | `console.warn({name}█)`                                             |
|  `cwj→` |   info with json                                                                                   | `console.warn('obj', JSON.stringify(obj, null, 2))█`                |
|   `ct→` | [table](https://developer.mozilla.org/en-US/docs/Web/API/Console/table)                            | `console.table(collection)█`                                        |
|   `ca→` | [assert](https://developer.mozilla.org/en-US/docs/Web/API/Console/assert)                          | `console.assert(expression, name)█`                                 |
|  `cdr→` | [dir](https://developer.mozilla.org/en-US/docs/Web/API/Console/dir)                                | `console.dir(name)█`                                                |
|  `ctr→` | [trace](https://developer.mozilla.org/en-US/docs/Web/API/Console/trace)                            | `console.trace(name)█`                                              |
|  `cts→` | [time start](https://developer.mozilla.org/en-US/docs/Web/API/Console/time)                        | `console.time(label)█`                                              |
|  `ctl→` | [time log](https://developer.mozilla.org/en-US/docs/Web/API/console/timeLog)                       | `console.timeLog(label)█`                                           |
|  `cte→` | [time end](https://developer.mozilla.org/en-US/docs/Web/API/console/timeEnd)                       | `console.timeEnd(label)█`                                           |
|  `ctg→` | [time group](https://developer.mozilla.org/en-US/docs/Web/API/Console/time)                        | <code>console.time(label)<br/>█<br/>console.timeEnd(label)</code>   |
|   `cc→` | [count](https://developer.mozilla.org/en-US/docs/Web/API/Console/count)                            | `console.count(label)█`                                             |
|  `ccr→` | [count reset](https://developer.mozilla.org/en-US/docs/Web/API/Console/countReset)                 | `console.countReset(label)█`                                        |
|  `cgs→` | [group start](https://developer.mozilla.org/en-US/docs/Web/API/Console/group)                      | `console.group(label)█`                                             |
|  `cge→` | [group end](https://developer.mozilla.org/en-US/docs/Web/API/console/groupEnd)                     | `console.groupEnd(label)█`                                          |
|  `cgg→` | [time group](https://developer.mozilla.org/en-US/docs/Web/API/Console/time)                        | <code>console.group(label)<br/>█<br/>console.groupEnd(label)</code> |
|  `clr→` | [clear](https://developer.mozilla.org/en-US/docs/Web/API/Console/clear)                            | `console.clear()█`                                                  |

### Styles

| Trigger | Description                     | Result CSS                                                                                            |
| ------: | ------------------------------- | ----------------------------------------------------------------------------------------------------- |
|   `co→` | outline                         | `outline: 1px solid limegreen !important;█`                                                           |
|   `cb→` | background                      | `background: rgb(0 100 0 / 0.2) !important;█`                                                         |
|  `cob→` | outline and background          | <code>outline: 1px solid limegreen !important;<br/>background: rgb(0 100 0 / 0.2) !important;█</code> |

⇧ [Back to menu](#menu)

---

## About

### Built With

- [VS Code](https://code.visualstudio.com/) - Code editing redefined.
- [Figma](https://www.figma.com/) - The collaborative interface design tool.

### Sources

- [MDN Debugger](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/debugger)
- [MDN Console](https://developer.mozilla.org/en-US/docs/Web/API/console)
- [Debug CSS with background and outlines](https://codepen.io/kevinpowell/pen/XWZBwWz)
- [Box Model](https://codepen.io/carolineartz/pen/ogVXZj)

### Contributing

Please read [CONTRIBUTING](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [Debug Snippets](https://github.com/deinsoftware/vscode-debug-snippets/tags) on GitHub.

### Authors

- **Camilo Martinez** [[Equiman](http://github.com/equiman)]

See also the list of [contributors](https://github.com/deinsoftware/vscode-debug-snippets/contributors) who participated in this project.

### Sponsors

If this project helps you, consider buying me a cup of coffee.

[![paypal](https://img.shields.io/badge/-PayPal-gray?style=flat&labelColor=00457C&logo=paypal&logoColor=white&link=https://paypal.me/equiman/3)](https://paypal.me/equiman/3)
[![ko-fi](https://img.shields.io/badge/-Ko–Fi-gray?style=flat&labelColor=fd444a&logo=ko-fi&logoColor=white&link=https://ko-fi.com/equiman)](https://ko-fi.com/equiman)

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

⇧ [Back to menu](#menu)
