## About Me theme for Spress

"About me" a single page, single screen responsive theme ideal for creating your business card. 
"About me" is a theme for Spress inspired by Aerial from [HTML5 UP](http://html5up.net).
[Live demo](http://spress-add-ons.github.io/about-me/).

### License 
Free for personal and commercial use under the [CCA 3.0 license](https://creativecommons.org/licenses/by/3.0/).

### Featured:

* Responsive design: Support to mobile and tablets.
* Easy configuration. You only need to modify the `config.yml` file with your name, bio, interests and social networks.

### How to install?

Go to your [Spress](http://spress.yosymfony.com/) installation folder i.e  **~/Spress** and add the following depencency to your `composer.json` file 

```
"require": {
    "spress-add-ons/about-me-theme": "1.0.*@dev"
}
```

and then run the following command to install the dependency.

```
$ composer update
```

### How to use?

**Create a new site**:

```bash
$ spress new:site /your-site-dir about-me
$ cd /your-site-dir directive
$ spress site:build --server --watch
```
