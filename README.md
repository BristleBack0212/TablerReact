# Update - June 2019: Version 2

Alpha now available on NPM:

`npm install tabler-react@alpha`
`yarn add tabler-react@alpha`

## Install

Make sure you have Node.js 8+ and yarn installed.

`yarn add tabler-react`

## Example

```jsx
import React, { Component } from "react";

import "tabler-react/dist/Tabler.css";

import { Card, Button } from "tabler-react";

class MyCard extends Component {
  render() {
    return (
      <Card>
        <Card.Header>
          <Card.Title>Card Title</Card.Title>
        </Card.Header>
        <Card.Body>
          <Button color="primary">A Button</Button>
        </Card.Body>
      </Card>
    );
  }
}
```

## Contributing

There are plenty of opportunities to get involved. Pick an outstanding task, let us know what you are working on and fire away with any questions.

The package is made up of 2 main folders:

- /src contains all the Tabler React components
- /example is our create-react-app based demo website

To setup and run a local copy:

1.  Clone this repo 
2.  Run `yarn install` in the root folder
3.  Run `yarn install` in the example folder
4.  In seperate terminal windows, run `yarn start` in the root and example folders.

You should now be up and running with live browser reloading of the example website while you work on Tabler React components in the /src folder.

When you're done working on your changes, submit a PR with the details and include a screenshot if you've changed anything visually.