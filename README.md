# unit-test-vue

Setup unit test for vue
vue create unit-test-vue
manual setup > unit testing > ESLint + AirBnb config > Lint on save > Jest > In dedicated config files

To run unit test:
npm run unit:test
```
shallowMount: due provided test utility to mount components for testing
The shallowMount method creates and mounts the component for us where if that component has any child components
They are not rendered
shallowMount returns to us a wrapper around our mounted component where that
Wrapper has some extra convenience functions that make testing easier
One of them is the text function which return a string of what was rendered
We set up a assertion where we expected the wrapper.text matches the regular expression Blog Widget
In the HelloWorld.vue <h1>{{ msg }}</h1> is rendered out

expect(wrapper.text()).toMatch(msg);
```

