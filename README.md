[![Bazzite Project](https://img.shields.io/badge/Bazzite-project-blue.svg)](https://statusfy.co)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/afb1b57affaa4f5d8fcaac5c0beee5c0)](https://www.codacy.com/app/bazzite/statusfy?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=bazzite/statusfy&amp;utm_campaign=Badge_Grade)
[![Travis](https://img.shields.io/travis/bazzite/statusfy.svg)](https://travis-ci.org/bazzite/statusfy)
[![David](https://img.shields.io/david/bazzite/statusfy.svg)](https://david-dm.org/bazzite/statusfy)
[![David](https://img.shields.io/david/dev/bazzite/statusfy.svg)](https://david-dm.org/bazzite/statusfy?type=dev)
[![Greenkeeper badge](https://badges.greenkeeper.io/bazzite/statusfy.svg)](https://greenkeeper.io/)
[![version](https://img.shields.io/npm/v/statusfy.svg)](https://www.npmjs.com/package/statusfy)
[![License](https://img.shields.io/github/license/bazzite/statusfy.svg)][license-page]
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fbazzite%2Fstatusfy.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fbazzite%2Fstatusfy?ref=badge_shield)

<p align="center">
  <a href="https://statusfy.co?utm_source=github&utm_medium=readme&utm_campaign=statusfy" target="_blank">
    <img src="https://raw.githubusercontent.com/bazzite/statusfy/develop/packages/docs/src/.vuepress/public/assets/img/statusfy-home-en.png" alt="Statusfy" />
  </a>
</p>

# Statusfy

> A marvelous Open Source Status Page system

Statusfy is a Status Page System, easy to use and completely Open Source. You can easily create a fast System either [**Static Generated**](https://docs.statusfy.co/guide/architecture.html#static-generated) or [**Server Rendered**](https://docs.statusfy.co/guide/architecture.html#server-rendered) and easily deploy it to a variety of [hosting services](https://docs.statusfy.co/guide/deploy.html).

A Statusfy site is a Web Application, created with [Vue][vue], [Nuxt.js][nuxt] and [Tailwind CSS][tailwindcss]. We use **Vue** to dynamically define the interfaces that represent the data, **Nuxt.js** to make a quick and useful abstraction of the client and server logic, and **Tailwind CSS** to rapidly define the default theme.

## Install

``` bash
# install dependencies
$ yarn add vuepress -D
```

## Development

:warning: You must at least use `node >= 8.10`.

``` bash
# install dependencies
yarn
# serves Statusfy's own demo
yarn demo:dev 
# make sure your code change pass the test
yarn test
```

## Demo

A Demo application is at [https://demo.statusfy.co][demo].

## Documentation & Support

If you want extra details of how to configure and use this project, the **full documentation** is available at [https://docs.statusfy.co][documentation].

You may want to check the examples projects for different popular hosting services at [the Examples Repository][examples].

For **Bug reports** or **Feature requests**, use the [Issues section][issues].

For **questions**, go to [https://stackoverflow.com/questions/ask?tags=statusfy](https://stackoverflow.com/questions/ask?tags=statusfy).

You can find usefull **articles** in [our blog][statusfy-blog].

You may also want to [follow the company supporting this project on Twitter][twitter].

### Commercial Support

This project is sponsored by [Bazzite][bazzite-website]. If you require professional assistance on your project(s), please contact us at [https://statusfy.co/support][support-page].

## Contributing

Please make sure to read the [Contributing Guide][contributing] before making a pull request.

## Code of Conduct

Everyone participating in this project is expected to agree to abide by the [Code of Conduct][code-of-conduct].

## License

Code released under the [Apache License 2.0][license-page].

[examples]: https://github.com/bazzite/statusfy-examples
[demo]: https://demo.statusfy.co?utm_source=github&utm_medium=readme&utm_campaign=statusfy
[documentation]: https://docs.statusfy.co?utm_source=github&utm_medium=readme&utm_campaign=statusfy
[contributing]: https://github.com/bazzite/statusfy/blob/develop/CONTRIBUTING.md
[code-of-conduct]: https://www.bazzite.com/open-source/code-of-conduct?utm_source=github&utm_medium=readme&utm_campaign=statusfy
[issues]: https://github.com/bazzite/statusfy/issues
[twitter]: https://twitter.com/BazziteTech
[bazzite-website]: https://www.bazzite.com?utm_source=github&utm_medium=readme&utm_campaign=statusfy
[support-page]: https://statusfy.co/support?utm_source=github&utm_medium=readme&utm_campaign=statusfy
[statusfy-blog]: https://statusfy.co/blog?utm_source=github&utm_medium=readme&utm_campaign=statusfy
[license-page]: https://github.com/bazzite/statusfy/blob/develop/LICENSE
[vue]: http://vuejs.org/
[nuxt]: https://nuxtjs.org/
[tailwindcss]: https://tailwindcss.com/
