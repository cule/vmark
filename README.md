> __💖 Using webpack? You may want <a href="https://github.com/egoist/vmark-loader">vmark-loader</a> ➡️__

# vmark

[![NPM version](https://img.shields.io/npm/v/vmark.svg?style=flat)](https://npmjs.com/package/vmark) [![NPM downloads](https://img.shields.io/npm/dm/vmark.svg?style=flat)](https://npmjs.com/package/vmark) [![CircleCI](https://circleci.com/gh/egoist/vmark/tree/master.svg?style=shield)](https://circleci.com/gh/egoist/vmark/tree/master)  [![donate](https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&style=flat)](https://github.com/egoist/donate) [![chat](https://img.shields.io/badge/chat-on%20discord-7289DA.svg?style=flat)](https://chat.egoist.moe)

## Install

```bash
yarn add vmark
```

## Usage

In:

```markdown
# Show off some counter

<counter :start="0" />

<script>
import counter from './counter.vue'
export default {
  components: {
    counter
  }
}
</script>
```

Out:

```js
<template>
  <div class="vmark">
    <h1>Show off some counter</h1>
    <counter :start="0" />
  </div>
</template>

<script>
import counter from './counter.vue'
export default {
  components: {
    counter
  }
}
</script>
```

Code:

```js
const component = vmark(input)
// Get the component in SFC format
```



## API

### vmark(input)

#### input

Type: `string`<br>
Required: `true`

Input markdown string.

#### options

##### options.markdown

Options for [markdown-it](https://markdown-it.github.io/markdown-it/).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## Author

**vmark** © [egoist](https://github.com/egoist), Released under the [MIT](./LICENSE) License.<br>
Authored and maintained by egoist with help from contributors ([list](https://github.com/egoist/vmark/contributors)).

> [github.com/egoist](https://github.com/egoist) · GitHub [@egoist](https://github.com/egoist) · Twitter [@_egoistlily](https://twitter.com/_egoistlily)
