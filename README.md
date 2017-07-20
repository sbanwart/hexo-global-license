# hexo-global-license
---------------------

A generator for Hexo that adds a license statement to every page. It natively 
supports [Creative Commons v4.0](https://creativecommons.org/) or a custom license template.

## Installation

```
npm install hexo-global-license
```

## Usage

* Add settings to the Hexo configuration file
    * licenseType: Specify the type of Creative Commons license, or custom.
        * by: CC Attribution
        * by-nd: CC Attribution-NoDerivatives
        * by-sa: CC Attribution-ShareAlike
        * by-nc: CC Attribution-NonCommercial
        * by-nc-nd: CC Attribution-NonCommercial-NoDerivatives
        * by-nc-sa: CC Attribution-NonCommercial-ShareAlike
        * custom: Specify your own custom license HTML

### Examples

Creative Commons
```toml
licenseType: by-sa
licenseIconSize: normal
```

Custom
```toml
licenseType: custom
customLicense: <div>My custom license text.</div>

## License

Copyright (c) 2017, Scott Banwart. Licensed under the [MIT license](https://github.com/sbanwart/hexo-global-license/blob/master/LICENSE).
