# &lt;Login-Flip&gt;

> Web Component Login Flip using [Polymer](http://www.polymer-project.org/).

## Demo

[Check it live!](http://dancasttro.github.io/login-flip)

## Install

Install

The best way to install the component is using Bower:

`$ bower install login-flip --save`

[download as ZIP](https://github.com/dancasttro/login-flip/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="dist/login-flip.html">
    ```

3. Start using it!

    ```html
    <login-flip></login-flip>
    ```
    
Note: There are some visibility Problems with Firefox

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

* To build the distribution files before releasing a new version.

    ```sh
    $ grunt build
    ```

* To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/dancasttro/login-flip/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
