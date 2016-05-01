# paperback-example

> An example of how to use [paperback](https://github.com/dustinspecker/paperback)

## Demo

To try out `paperback` using this repository:

1. Clone this repository

```bash
git clone https://github.com/dustinspecker/paperback-example
```

1. Navigate to the clone `paperback-example` directory

```bash
cd paperback-example
```

2. Install `paperback`

```bash
npm install --global paperback
```

**Note: `Node` and `npm` must be installed to use `paperback`.**

3. Run `paperback` to generate more components

```bash
paperback
```

`paperback` will ask which page should be generated. This example only has one to choose from, so select it. Then `paperback` will ask a question loaded from [prompts.js](pages/src/components/__name__/prompts.js). Then `paperback` will scaffold the new component from all files found in [pages/src/component/\_\_name\_\_](pages/src/components/__name__/).

## LICENSE
MIT © [Dustin Specker](https://github.com/dustinspecker)
