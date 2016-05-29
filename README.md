# &lt;datetime-local-input&gt;

> A polymer datetime-local component

## Demo

[Check it live!](http://greenyouse.github.io/datetime-local-input)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install greenyouse-datetime-local-input --save
```

Or [download as ZIP](https://github.com/greenyouse/datetime-local-input/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/datetime-local-input/datetime-local-input.html">
    ```

3. Start using it!

    ```html
    <datetime-local-input></datetime-local-input>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`errorMessage`         | *string*    | `Please provide a full date` | An error message
for when validation fails
`label`         | *string*    | `Date`        | The input label
`value`         | *string*    | `bar`        | An error message

## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`validate()`   | None.        | Boolean    | Checks that the input value
is a datetime-local time.

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [bower](http://bower.io/) & [polyserve](https://npmjs.com/polyserve):

    ```sh
    $ npm install -g bower polyserve
    ```

2. Install local dependencies:

    ```sh
    $ bower install
    ```

3. Start development server and open `http://localhost:8080/components/my-repo/`.

    ```sh
    $ polyserve
    ```

## History

For detailed changelog, check [Releases](https://github.com/greenyouse/datetime-local-input/releases).

## Contribute!

There are a few issues that could use some help. Take a look at the
[issues](https://github.com/greenyouse/datetime-local-input/issues) for more.

## License

[MIT License](http://opensource.org/licenses/MIT)
