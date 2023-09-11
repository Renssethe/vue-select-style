# vue-select-style !

> **Everything you wish the HTML `<select>` element could do, wrapped up into a lightweight, zero
> dependency, extensible Vue component.**

Vue Select Style is a feature rich select/dropdown/typeahead component. It provides a default
template that fits most use cases for a filterable select dropdown. The component is designed to be
as lightweight as possible, while maintaining high standards for accessibility, developer
experience, and customization.

Vue Select Style is a fork of [vue-select](https://github.com/sagalbot/vue-select) with a new
template and some new features.

## Get started

**Vue 3 / Vue Select Style 4.x-beta**

> Vue 3 support is on the `beta` channel: `vue-select-style@beta`, and will become the new default when `v4` is released. See [#1579](https://github.com/sagalbot/vue-select/issues/1597) for more details!

Install:

```bash
yarn add vue-select-style

# or use npm

npm install vue-select-style
```

Then, import and register the component:

```js
# main.ts or main.js

import { createApp } from "vue";
import App from "./App.vue";

import { VueSelectStyle } from "vue-select-style";

createApp(App)
    .component("v-select-style", VueSelectStyle)
    .mount("#app");
```

The component itself does not include any CSS. You'll need to include it separately in your Component.vue:
```vue
<style>
@import "vue-select/dist/vue-select.css";
</style>
```

**Vue 2 / Vue Select 3.x**

Install:

```bash
yarn add vue-select-style

# or use npm

npm install vue-select-style
```

Then, import and register the component:

```js
import Vue from "vue";
import vSelectStyle from "vue-select-style";

Vue.component("v-select-style", vSelectStyle);
```

The component itself does not include any CSS. You'll need to include it separately:

```js
import "vue-select/dist/vue-select.css";
```

## License

[MIT](https://github.com/Renssethe/vue-select-style/blob/main/LICENSE.md)
