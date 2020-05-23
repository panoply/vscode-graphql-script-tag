[![Install](https://img.shields.io/badge/vscode-install-blue.svg)](https://marketplace.visualstudio.com/items?itemName=sissel.graphql-script-tag)

# GraphQL syntax support in HTML Scripts

Syntax highlighting support for HTML `<script></script>` tags using `application/graphql` and `application/ld+json` attributes. Uses an grammars provided by [graphql-for-vscode](https://github.com/kumarharsh/) by Kumar Harsh and thus uses this extension as a dependency. Does not support IntelliSense (yet) just provides syntax highlighting.


## Why?

Made available as per request from a developer.

## Example

```html
<script type="application/graphql">
  query User($id: ID!)
    user(id: $id) {
      name
      picture
    }
  }
</script>
```

## License

[MIT](LICENSE)
