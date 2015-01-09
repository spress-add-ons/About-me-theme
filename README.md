## About Me theme for Spress

"About me" a single page, single screen responsive theme ideal for creating your business card. 
This theme for Spress has been inspired by Aerial from [HTML5 UP](http://html5up.net).

[Live demo](http://spress-add-ons.github.io/about-me/).

### Featured:

* Responsive design: Support to mobile and tablets.
* Easy configuration. You only need to modify the `config.yml` file with your name, bio, interests and social networks.

### How to install?

#### With Git

* [Fork this repository](https://github.com/spress-add-ons/About-me-theme/fork)
* Clone it: ` https://github.com/YOUR-USER/About-me-theme.git
* Go to `About-me-theme folder
* `spress site:build --server --watch`

#### Globally

Go to your [Spress](http://spress.yosymfony.com/) installation folder i.e  **~/Spress** and add the following depencency to your `composer.json` file 

```
"require": {
    "spress-add-ons/about-me-theme": "1.0.*@dev"
}
```

and then run the following command to install the dependency.

```bash
$ composer update
```

Next create your new site:

```bash
$ spress new:site /your-site-dir about-me
$ cd /your-site-dir
$ spress site:build --server --watch
```

### License 
Free for personal and commercial use under the [CCA 3.0 license](https://creativecommons.org/licenses/by/3.0/).
