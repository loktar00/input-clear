# &lt;input-clear&gt;

> Very simple web component which is a text input allowing you to clear contents with inline x using [VanillaJS](http://vanilla-js.com/).

## Demo

[Check out the live demo](http://loktar00.github.io/input-clear)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install input-clear --save
```

Or [download as ZIP](https://github.com/loktar00/input-clear/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/input-clear/src/input-clear.html">
    ```

3. Start using it!

    ```html
    <input-clear></input-clear>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`placeholder`         | *string*    | `bar`        | Standard input text placeholder.

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/):

    ```sh
    $ [sudo] npm install -g bower
    ```

* Install local dependencies:

    ```sh
    $ bower install
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/loktar00/input-clear/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)