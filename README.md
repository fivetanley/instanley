Install-Install
===============

There are too many package managers for your projects nowadays. To install
with Bundler, NPM, Bower, Leiningen or Maven:

`install-install`

Install-Install will only run the command if its corresponding file is present.
For example:

* Bundler will run if a `Gemfile` is present
* `npm install` will run if a `package.json` is present
* `bower install` will run if a `bower.json` is present.
* `lein deps` will run if a `project.clj` is present
* `mvn dependency:resolve` will run if a `pom.xml` is present

# Installation

Add `install-install` to your PATH. For example, make a `bin` folder in your `$HOME`
and put the following in your `.bashrc` or `.zshrc`:

`export PATH=$HOME/bin:$PATH`

## License

MIT. See the included `LICENSE` folder in this repository.
