# Hyo :mount_fuji:
\- A light-weight datatable for React.

![hyo](https://s9.postimg.org/u0qnah3bz/Hyo.gif?noredir=1 "Hyo")

## Getting Started

### Installation
Hyo is now available from the npm package manager. Navigate to your project folder, and you can install it with the following commands

* `yarn add hyo` - Using yarn.
* `npm install --save hyo` - Using npm.

Then import styles by including our `style.min.css`

* ``<link rel="stylesheet" href="node_modules/hyo/style.min.css">``

### Your First Table
With only two props, you can make your first Hyo table.
``` javascript
  import Table from 'hyo';

  const def = [
    { key: "name", label: "Name", flexGrow: 1, resizable: true },
    { key: "gender", label: "Gender", flexGrow: 1 },
  ];

  const data = [
    { name: "Mars", gender: "Male" },
    { name: "Tony", gender: "Male" },
  ];

  return <Table def={def} data={data} />;`
```
* For more examples, see [LiveDemo](http://hyo-mars.herokuapp.com/) and [Documentation](https://marswang92.github.io/hyo/).

