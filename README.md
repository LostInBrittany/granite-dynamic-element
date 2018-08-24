[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/LostInBrittanygranite-dynamic-element)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/LostInBrittanygranite-dynamic-element.svg)](https://vaadin.com/directory/component/LostInBrittanygranite-dynamic-element)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/LostInBrittany/granite-dynamic-element)

# granite-dynamic-element

> A native web component to dynamically generate web components


## Usage example

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="granite-dynamic-element.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<granite-dynamic-element name="h1" slot="Hello my friend!" attr1="passed to child" another-random-attribute="also passed to child">
</granite-dynamic-element>
<granite-dynamic-element name="a" slot="Link to granite-dynamic-element GitHub" href="https://github.com/LostInBrittany/granite-dynamic-element">
</granite-dynamic-element>
```

## Demo

https://lostinbrittany.github.io/granite-dynamic-element/components/granite-dynamic-element/demo/index.html


## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install LostInBrittany/granite-dynamic-element --save
```

Or [download as ZIP](https://github.com/LostInBrittany/granite-dynamic-element/archive/gh-pages.zip).## Usage

1. Import Web Components' polyfill (if needed):

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/granite-dynamic-element/granite-dynamic-element.html">
    ```

3. Start using it!

    ```html
    <granite-dynamic-element 
        name="a" slot="Link to granite-dynamic-element GitHub" 
        href="https://github.com/LostInBrittany/granite-dynamic-element">
    </granite-dynamic-element>
    ```


## Attributes

Attribute     | Type      | Default  | Description
---           | ---       | ---      | ---
`name`        | *String*  | `none`   | The child element name (either native or web component)
`slot`        | *String*  | `''`     | The child element inner HTML


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)
