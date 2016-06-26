# Linting and Editorconfig

Reference repo for [eslint][eslint] (and other linters) as well as [editorconfig][editorconfig]
settings and info

Contains:

- an example `.editorconfig` with some reasonable defaults
- example of "pure" [AirBnB JavaScript][airbnb] eslint setup (complete with React)
- example of a "customised" AirBnB set up based on the above
- an example `.scss-lint.yml` with some reasonable defaults for [scss-lint](https://github.com/brigade/scss-lint)
- an example `.stylintrc` with some reasonable defaults for [stylint](https://github.com/rossPatton/stylint)
- an example `.markdownlintrc` file to configure markdownlint [node](https://github.com/DavidAnson/markdownlint)/[ruby](https://github.com/mivok/markdownlint)

### The whys and wherefores

Although we don't want to enforce any kind of "one true way" to code, we _would_ like for any given project to be able to enforce its own coding style choices (tabs, spaces, single quotes, etc).

Linting can also encourage best practices (function names, etc) and even catch some errors nice and early (typos).

### Linting and a Suggested JavaScript Baseline

I am proposing [AirBnB JavaScript][airbnb] using ESLint as the baseline standard. It is an extensive set of reasonable standards and even covers React and JSX.

Moreover, unlike something like [standard][standard] or [semistandard][semistandard] which are meant to be all-or-nothing bikeshed breakers, AirBnB is just an eslint config that can have any individual rule overridden at a project level.

Examples of "pure" AirBnB and customised AirBnB are in the [linting repo][linting-repo].

@garthdb has also added in linting configs for styles and markdown, currently in use by the site.

### Editorconfig

> EditorConfig helps developers define and maintain consistent coding styles between different editors and IDEs. The EditorConfig project consists of a file format for defining coding styles and a collection of text editor plugins that enable editors to read the file format and adhere to defined styles. EditorConfig files are easily readable and they work nicely with version control systems.

Most of the major editors and IDEs can respect [editorconfig][editorconfig] files that specify things like tabs over spaces, how many spaces, etc. There is also an example of one of these in the repo. Setting one of these up will help others to respect the choices you make wrt these styles.

### Git Collaboration Workflow

Also included is a simple CONTRIBUTING.md file with basic collaboration / contribution information.


[eslint]: http://eslint.org
[editorconfig]: http://editorconfig.org
[airbnb]: https://github.com/airbnb/javascript
[airbnb]: https://github.com/airbnb/javascript
[standard]: http://standardjs.com/
[semistandard]: https://github.com/Flet/semistandard
[linting-repo]: https://github.com/phonegap/linting-and-editorconfig
[editorconfig]: http:/editorconfig.org
[ccg]: https://cordova.apache.org/contribute/contribute_guidelines.html
