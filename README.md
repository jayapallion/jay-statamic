<p align="center"><img src="https://statamic.com/assets/branding/Statamic-Logo+Wordmark-Rad.svg" width="400" alt="Statamic Logo" /></p>


## Setup Guide

- Follow installation guide : [https://statamic.dev/installing/laravel-herd](url)  -> Note: make sure to create your superuser, if not, you can do it later with command `php please make:user`
  
- If composer is not installed : 
    - curl -sS https://getcomposer.org/installer -o composer-setup.php
    - php composer-setup.php
    - sudo mv composer.phar /usr/local/bin/composer
    - composer --version
    - composer global require statamic/cli
    - composer global config bin-dir --absolute
 
- Download the project and name it as "sendx-cms" and move the folder to `Sites` folder at your root and run following commands in `Sites` folder : 
    - valet install
    - valet park
    - valet restart
 
- Then you can access the site at : `http://sendx-cms.test`
  
- And you can access control panel from : `http://sendx-cms.test/cp/dashboard`


## About Statamic

Statamic is the flat-first, Laravel + Git powered CMS designed for building beautiful, easy to manage websites.

> [!NOTE]
> This repository contains the code for a fresh Statamic project that is installed via the Statamic CLI tool.
>
> The code for the Statamic Composer package itself can be found at the [Statamic core package repository][cms-repo].


## Learning Statamic

Statamic has extensive [documentation][docs]. We dedicate a significant amount of time and energy every day to improving them, so if something is unclear, feel free to open issues for anything you find confusing or incomplete. We are happy to consider anything you feel will make the docs and CMS better.

## Support

We provide official developer support on [Statamic Pro](https://statamic.com/pricing) projects. Community-driven support is available on the [forum](https://statamic.com/forum) and in [Discord][discord].


## Contributing

Thank you for considering contributing to Statamic! We simply ask that you review the [contribution guide][contribution] before you open issues or send pull requests.


## Code of Conduct

In order to ensure that the Statamic community is welcoming to all and generally a rad place to belong, please review and abide by the [Code of Conduct](https://github.com/statamic/cms/wiki/Code-of-Conduct).


## Important Links

- [Statamic Main Site](https://statamic.com)
- [Statamic Documentation][docs]
- [Statamic Core Package Repo][cms-repo]
- [Statamic Migrator](https://github.com/statamic/migrator)
- [Statamic Discord][discord]

[docs]: https://statamic.dev/
[discord]: https://statamic.com/discord
[contribution]: https://github.com/statamic/cms/blob/master/CONTRIBUTING.md
[cms-repo]: https://github.com/statamic/cms
