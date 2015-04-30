# Dokku [![Build Status](https://circleci.com/gh/progrium/dokku/tree/master.svg?style=svg&circle-token=eec5b442dda53a4d229911dd97d4214853acc262 "Build Status")](https://circleci.com/gh/progrium/dokku/tree/master) [![Ubuntu Package](https://img.shields.io/badge/package-ubuntu-brightgreen.svg?style=flat-square "Ubuntu Package")](https://packagecloud.io/dokku/dokku) [![IRC Network](https://img.shields.io/badge/irc-freenode-blue.svg "IRC Freenode")](https://webchat.freenode.net/?channels=dokku)

Docker powered mini-Heroku. The smallest PaaS implementation you've ever seen. Sponsored by our friends at [Deis](http://deis.io/).

## Requirements

- A fresh VM running Ubuntu `14.04 x64`

## Installing

To install the latest stable release, you can run the following commands as a user that has access to `sudo`:

    wget https://raw.github.com/progrium/dokku/v0.3.17/bootstrap.sh
    sudo DOKKU_TAG=v0.3.17 bash bootstrap.sh

### Upgrading

[View the docs for upgrading](http://progrium.viewdocs.io/dokku/upgrading) from an older version of Dokku.

## Documentation

Full documentation - including advanced installation docs - are available online at [docs](http://progrium.viewdocs.io/dokku/index)

## Support

You can use [Github Issues](https://github.com/progrium/dokku/issues), check [Troubleshooting](http://progrium.viewdocs.io/dokku/troubleshooting) in the documentation, or join us on [freenode in #dokku](https://webchat.freenode.net/?channels=%23dokku)

## Contribution

After checking [Github Issues](https://github.com/progrium/dokku/issues), the [Troubleshooting Guide](http://progrium.viewdocs.io/dokku/troubleshooting) or having a chat with us on [freenode in #dokku](https://webchat.freenode.net/?channels=%23dokku), feel free to fork and create a Pull Request.

While we may not merge your PR as is, they serve to start conversations and improve the general dokku experience for all users.

## Sponsors

Dokku is currently sponsored by the enterprise grade, multi-host PaaS project [Deis](http://deis.io/).

## License

MIT
