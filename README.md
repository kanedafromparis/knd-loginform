# &lt;knd-loginform&gt;

> A Web Component example using [Polymer](http://www.polymer-project.org/).
>
> Looking for a boilerplate? Check [polymer-boilerplate](https://github.com/webcomponents/polymer-boilerplate).

## Demo

<!-- [Check it live!](http://kanedafromparis.github.io/polymer-demo/knd-loginform/demo.html) -->

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install knd-loginform --save
```

<!-- Or [download as ZIP](https://github.com/kanedafromparis/knd-loginform/archive/master.zip). -->

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/knd-loginform/knd-loginform.html">
    ```
    <!-- se pause la question de grunt pour avoir un dossier "dist" -->

3. Start using it!

    ```html
    <knd-loginform>some regular texte</knd-loginform>
    ```

## Options
@todo
<!--
Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`who`      | *string*                  | `World`             | Who do you want to say hello?
---        | ---                       | ---                 | ---
`who`      | *string*                  | `World`             | Who do you want to say hello?
---        | ---                       | ---                 | ---
`who`      | *string*                  | `World`             | Who do you want to say hello?
---        | ---                       | ---                 | ---
`who`      | *string*                  | `World`             | Who do you want to say hello?
---        | ---                       | ---                 | ---
`who`      | *string*                  | `World`             | Who do you want to say hello?
---        | ---                       | ---                 | ---
`who`      | *string*                  | `World`             | Who do you want to say hello?

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

1. Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

2. Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

3. To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

4. To build the distribution files before releasing a new version.

    ```sh
    $ grunt build
    ```

5. To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```
-->
## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/webcomponents/hello-world-polymer/releases).

## License

[LGPL License](https://www.gnu.org/licenses/lgpl.html)