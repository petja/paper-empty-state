# Empty state

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/petja/paper-empty-state)

Element automatically observers array given to it and shows [empty state](https://material.io/guidelines/patterns/empty-states.html) whenever the array is empty. And when array gets its contents, we'll automatically switch to your custom HTML. However, you can also use this element standalone without any arrays, then we just show empty state always.

## Demos

### Customize text and the icons

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="paper-empty-state.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-empty-state text="Hello world" icon="backup"></paper-empty-state>
```

### Automatically toggle empty state

* Array without contents, shows an empty state
* Array with contents, shows your custom HTML

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="paper-empty-state.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-empty-state items="[]">Custom content</paper-empty-state>
<hr />
<paper-empty-state items="['a', 'b', 'c']">Custom content</paper-empty-state>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

MIT License

[Checkout LICENSE file](LICENSE)
