# Homebrew tap for Kontena

This repository is a "[tap](https://github.com/Homebrew/brew/blob/master/docs/Taps.md)" for the popular macOS package manager [Homebrew](https://github.com/Homebrew/brew)
and hosts formulae for the [Kontena](https://www.kontena.io/) command-line client.

Kontena CLI is also available in the main [homebrew-core](https://github.com/Homebrew/homebrew-core).
This tap provides access to development versions and instant access to stable releases when released.

It takes some time before stable releases are updated to homebrew-core, by using this tap you can get
the latest version without delay.

### About Kontena

[Kontena](https://www.kontena.io) is a new developer friendly, open source platform for orchestrating applications that are run on Docker containers. It simplifies deploying and running containerized applications on any infrastructure. By leveraging technologies such as [Docker](https://www.docker.com/), [CoreOS](https://coreos.com/) and [Weave](https://www.weave.works/), it provides complete solution for organizations of any size.

Kontena is built to maximize developer happiness; it is designed for application developers and therefore does not require ops teams to setup or maintain. Therefore, it is an ideal choice for organizations without aspiration to configure and maintain scalable Docker container infrastructure.

Kontena supports any application that can run in a Docker container, and can run on any machine that supports CoreOS. You can run Kontena on the cloud provider of your choice or on your own servers.

- [Kontena Website](https://www.kontena.io)
- [Kontena Blog](http://blog.kontena.io)
- [Documentation](https://www.kontena.io/docs)
- [GitHub](https://github.com/kontena/kontena)

## Usage

You can install Kontena CLI through this repository by using:

```
brew install kontena/kontena/kontena
```

### Development releases

The latest development release can be installed by using:

```
brew install --devel kontena/kontena/kontena
```

### Bleeding edge version

It's also possible to install a version built directly from the sources in the master development
branch of kontena:

```
brew install --HEAD kontena
```

This is also possible from the homebrew-core without subscribing to this tap.

### Previous versions

To install a specific version, you must check out a tag for that version:

```
cd $(brew --repo kontena/kontena)
git checkout 1.4.1.rc1
brew install --devel kontena/kontena/kontena
git checkout master
```

### Switching between versions

If you have multiple versions installed, you can switch between them by using:

```
brew switch kontena 1.4.1.rc1
```

## Contact Us

Found a bug? Suggest a feature? Have a question? Please [submit an issue](https://github.com/kontena/homebrew-kontena/issues) or email us at <a href="mailto:info@kontena.io">info@kontena.io</a>.

Follow us on Twitter: [@KontenaInc](https://twitter.com/KontenaInc).

Slack: [Join the Kontena Community Slack channel](https://slack.kontena.io/).
