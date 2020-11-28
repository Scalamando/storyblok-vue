# Vue Storyblok plugin

Make any element editable with the Vue Storyblok directive. Just add ```v-editable="content"``` to a html element.

## Compatibility

Requires Vue 3.0

## Install

```
npm install storyblok-vue-3 --save-dev
```

## Usage

In your entry point:

```
import StoryblokVue3 from 'storyblok-vue-3'

const app = createApp({...}).use(StoryblokVue3).mount('...');
```

In the template:
```
<div v-editable="demo">
  Test
</div>
```

## License

[MIT](http://opensource.org/licenses/MIT)
