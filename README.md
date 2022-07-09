# enterprise-rust-template

[![Bors enabled](https://bors.tech/images/badge_small.svg)](https://app.bors.tech/repositories/46479)

This is an _opinionated_ template repository for rust projects.
It is "enterprise" because it contains _all the things_ you could ever want from
such a repository:

* bors
* CI
    * Builds for different platforms
        * alpine
        * archlinux
        * centos
        * debian
        * nixos
        * RHEL
        * static using musl
        * ubuntu
        * yocto
    * checks
        * clippy
        * coverage
        * cargo-deny
        * cargo-outdated
    * testing
    * crosscompilation
        * ARM
        * RISC-V
    * caching
* dependabot
* stalebot
* community automation
    * commit linting
    * first time contributor message
    * blocking of "!fixup"/"!squash" commits
    * automatic labeling
    * automatic assigning issues/PRs
    * automatic reviews
        * missspell checks
        * language checks
* github pages builds
    * Code documentation
    * website (using zola)
* Release automation
* Codeowners
* Badges
* Libraries
    * Common crates are set as dependencies for your convenience

## MSRV

MSRV for this repository is currently: 1.60.0

That matters explicitely because we run some tools only for this version, e.g.:
clippy.

## License

(c) 2022 Matthias Beyer

Licensed as MIT or Apache 2.0 or MPL or WTFPL _at your opinion_.
