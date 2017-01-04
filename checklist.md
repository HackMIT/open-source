# Open-sourcing checklist

## Before making a repository public

1. Check revision history for secrets and other sensitive content
    * Can be fixed using `git rebase [-i]` or `git filter-branch`
1. Choose an appropriate license and include it as a `LICENSE.txt` or `LICENSE.md` file
    * Make sure you understand the implications of choosing different licenses
    * Licenses we currently use:
        * MIT ([HELPq][helpq], [redisred][redisred], Hubot plugins)
        * GPLv3 ([OffiX][offix])
        * AGPLv3 ([Gavel][gavel])
1. Write a good `README.md`
    * Should contain:
        * Short description
        * Demo/screenshot
        * How to use it
        * How to install/deploy it
        * How to contribute
        * How it is licensed
    * [HELPq][helpq], [Gavel][gavel], and [redisred][redisred] are good examples

### Optional (recommended) steps

* Write a development guide
    * This makes it easy for new contributors to get started
    * Gavel has a pretty good [example](https://github.com/anishathalye/gavel/blob/master/DEVELOPMENT.md)
* Write a `CONTRIBUTING.md`
    * See [HELPq](https://github.com/ehzhang/HELPq/blob/master/CONTRIBUTING.md) or [Gavel](https://github.com/anishathalye/gavel/blob/master/CONTRIBUTING.md) for examples
* Set up good issue labels
    * See [Gavel](https://github.com/anishathalye/gavel/issues) for an example
* Close old / irrelevant issues

## Releasing a project

1. Add the project to [code.hackmit.org](https://code.hackmit.org/) ([hackmit-code](https://github.com/techx/hackmit-code) repo)
1. Make sure the project has a designated maintainer who will triage issues and review pull requests

### Optional (recommended) steps

* Write a [blog post](https://medium.com/hackmit-stories) about it
* Publicize the software in the Hackcon and Hackathon Hackers Facebook groups
* Publicize the software on our Twitter and our Facebook page
* Create some GitHub Issues on easy features or bugfixes to give new contributors a place to start

[helpq]: https://github.com/ehzhang/HELPq
[gavel]: https://github.com/anishathalye/gavel
[offix]: https://github.com/anishathalye/offix
[redisred]: https://github.com/Detry322/redisred
