<br><br>

<p align="center">
  <img src="https://raw.githubusercontent.com/reakit/reakit/master/logo/logo.png" alt="reakit" width="320" />
</p>

<br>

<p align="center">
  Toolkit for building <a href="https://reakit.io/guide/composability">composable</a>, <a href="https://reakit.io/guide/accessibility">accessible</a> and <a href="https://reakit.io/guide/reliability">reliable</a> UIs with <a href="https://reactjs.org">React</a>.
</p>

<br>

<p align="center">
  <a href="https://reakit.io"><strong>🌎 Website</strong></a> &nbsp; · &nbsp;
  <a href="https://reakit.io/guide"><strong>📚 Guide</strong></a> &nbsp; · &nbsp;
  <a href="https://reakit.io/components"><strong>🏗 Components</strong></a>
</p>

<br>

<p align="center">
  <a href="https://npmjs.org/package/reakit"><img alt="NPM version" src="https://img.shields.io/npm/v/reakit.svg?style=flat-square" /></a>
  <a href="https://travis-ci.org/reakit/reakit"><img alt="Build Status" src="https://img.shields.io/travis/reakit/reakit/master.svg?style=flat-square" /></a>
  <a href="https://codecov.io/gh/reakit/reakit/branch/master"><img alt="Coverage Status" src="https://img.shields.io/codecov/c/github/reakit/reakit/master.svg?style=flat-square" /></a>
  <a href="https://spectrum.chat/reakit"><img src="https://img.shields.io/badge/community-spectrum-7A2DFB.svg?style=flat-square" alt="Spectrum" /></a>
  <a href="https://join.slack.com/t/reakit/shared_invite/enQtNDExMDcwNTk2MTMwLWI1Mzk1Y2YzMTAzZGUyMGIzMjQxZGU4OGM3MDI0OTcyYWU0NzZjZmIxNDcxZTVlODZiODA3YjE5N2FiOWMxZWQ"><img src="https://img.shields.io/badge/chat-slack-DE215B.svg?style=flat-square" alt="Slack" /></a>
</p>

## Installation

```sh
npm i reakit
```

> Thanks to [@nosebit](https://github.com/nosebit) for the package name on npm.

## Example

<p align="center">
  <img
    src="https://user-images.githubusercontent.com/3068563/35465289-0cb7fe96-02e2-11e8-8bc5-60abcb6e92ac.gif"
    width="200"
  /><br>
  See and edit full source code on <a href="https://codesandbox.io/s/m4n32vjkoj">CodeSandbox</a>
</p>

```jsx
import React from "react";
import { render } from "react-dom";
import { Button, Popover } from "reakit";

const App = () => (
  <Popover.Container>
    {popover => (
      <Button as={Popover.Toggle} {...popover}>
        Toggle
        <Popover {...popover}>
          <Popover.Arrow />
          Popover
        </Popover>
      </Button>
    )}
  </Popover.Container>
);

render(<App />, document.getElementById("root"));
```


## Contributors

This project exists thanks to all the people who contribute.
<a href="https://github.com/reakit/reakit/graphs/contributors"><img src="https://opencollective.com/reakit/contributors.svg?width=890&button=false" /></a>


## Backers

Thank you to all our backers! 🙏

<a href="https://opencollective.com/reakit#backer" target="_blank"><img src="https://opencollective.com/reakit/backers.svg?width=890"></a>


## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website.<br>

<a href="https://opencollective.com/reakit/sponsor/0/website" target="_blank"><img src="https://opencollective.com/reakit/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/reakit/sponsor/1/website" target="_blank"><img src="https://opencollective.com/reakit/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/reakit/sponsor/2/website" target="_blank"><img src="https://opencollective.com/reakit/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/reakit/sponsor/3/website" target="_blank"><img src="https://opencollective.com/reakit/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/reakit/sponsor/4/website" target="_blank"><img src="https://opencollective.com/reakit/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/reakit/sponsor/5/website" target="_blank"><img src="https://opencollective.com/reakit/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/reakit/sponsor/6/website" target="_blank"><img src="https://opencollective.com/reakit/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/reakit/sponsor/7/website" target="_blank"><img src="https://opencollective.com/reakit/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/reakit/sponsor/8/website" target="_blank"><img src="https://opencollective.com/reakit/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/reakit/sponsor/9/website" target="_blank"><img src="https://opencollective.com/reakit/sponsor/9/avatar.svg"></a>

<a href="https://www.browserstack.com" target="_blank"><img src="https://user-images.githubusercontent.com/15015324/45184727-368fbf80-b1fe-11e8-8827-08dbc80b0fb1.png" width="200"></a>

## License

MIT © [Diego Haz](https://github.com/diegohaz)
