# generator-jhipster-bootswatch [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]
> A jhipster module to enable bootswatch theme switcher to generated application

# Notice

## Bootswatch is directly supported by latest versions of JHipster, so please use that instead

**Please note that this module is deprecated and only works with AngularJS and hence will not work with JHipster 5+ which supports only Angular and React**

## Usage

This is a [JHipster](http://jhipster.github.io/) module, that is meant to be used in a JHipster application.

This module will add a [bootswatch](https://bootswatch.com/) theme switcher to your application footer

![Screenshot 1](http://jhipster.github.io/images/009_tips_using_bootswatch_themes_03.png)

## Installation

As this is a [JHipster](http://jhipster.github.io/) module, we expect you have [JHipster and its related tools already installed](http://jhipster.github.io/installation.html).

This module requires Jhipster version greater than 2.26.2 in order to work

```bash
npm install -g generator-jhipster-bootswatch
```

Then run the module on a JHipster generated application:

```bash
yo jhipster-bootswatch
```

## Using Docker

Download the Dockerfile:

```bash
mkdir docker
cd docker
wget https://github.com/jhipster-projects/generator-jhipster-bootswatch/raw/master/docker/Dockerfile
```

Build the Docker images:

```bash
docker build -t jhipster-generator-bootswatch:latest .
```

Make a folder where you want to generate the Service:

```bash
mkdir service
cd service
```

Run the generator from image to generate service:

```bash
docker run -it --rm -v $PWD:/home/jhipster/app jhipster-generator-bootswatch
```

Run and attach interactive shell to the generator docker container to work from inside the running container:

```bash
docker run -it --rm -v $PWD:/home/jhipster/app jhipster-generator-bootswatch /bin/bash
```

## License

Apache-2.0 © [Deepu KS](http://deepu105.github.io)


[npm-image]: https://badge.fury.io/js/generator-jhipster-bootswatch.svg
[npm-url]: https://npmjs.org/package/generator-jhipster-bootswatch
[travis-image]: https://travis-ci.org/deepu105/generator-jhipster-bootswatch.svg?branch=master
[travis-url]: https://travis-ci.org/deepu105/generator-jhipster-bootswatch
[daviddm-image]: https://david-dm.org/hipster-labs/generator-jhipster-bootswatch.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/hipster-labs/generator-jhipster-bootswatch
