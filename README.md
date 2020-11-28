# Vue Storyblok plugin

Make any element editable with the Vue Storyblok directive. Just add ```v-editable="content"``` to a html element.

## Compatibility

Requires Vue 3.0

## Install

```
npm install storyblok-vue --save-dev
```

## Usage

In your entry point:

```
import StoryblokVue from 'storyblok-vue'

const app = createApp({...}).use(StoryblokVue).mount('...');
```

In the template:
```
<div v-editable="demo">
  Test
</div>
```

## License

[MIT](http://opensource.org/licenses/MIT)
