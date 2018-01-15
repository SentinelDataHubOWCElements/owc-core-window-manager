# \<owc-core-window-manager\>

This component manages the currently displayed components using the navigation stack, which is represented by an array of components. The first element in the array is the root, the dynamic-main-menu. The last element in the array is the last component displayed at the right of the screen (in Desktop view). The user can add components to the stack using the method pushComponent of navigation manager and can remove all components from the navigation stack, except for the root element, using the popComponent method. In Desktop view the new component is pushed on the right of the last visualized component, while in Mobile view the new component is pushed up to the currently visualized component.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
