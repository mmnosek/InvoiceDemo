# &lt;link is="juicy-redirect"&gt;

> Custom Element that changes redirects to a new URL when an attribute is changed. It can be configured to work using window location or History API.

## Demo

[Check it live!](http://juicy.github.io/juicy-redirect)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install juicy-redirect --save
```

Or [download as ZIP](https://github.com/juicy/juicy-redirect/archive/gh-pages.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="http://cdnjs.cloudflare.com/ajax/libs/polymer/0.3.1/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/juicy-redirect/src/juicy-redirect.html">
    ```

3. Start using it!

    ```html
    <link is="juicy-redirect" url=""></juicy-redirect>
    ```

## Attributes

Attribute      | Options            | Default  | Description
---            | ---                | ---      | ---
`url`          | *String*           |          | Destination URL
`url`          | `current`          |          | If a string `"curent"` is provided as the URL, the component reloads the page
`history`      |                    |          | If attributte `history` is present, the History API `pushState` is used instead of `window.location`

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/juicy/redirect/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
