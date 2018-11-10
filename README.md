# tfschema

[![CircleCI](https://circleci.com/gh/tmknom/tfschema.svg?style=svg)](https://circleci.com/gh/tmknom/tfschema)
[![Docker Build Status](https://img.shields.io/docker/build/tmknom/tfschema.svg)](https://hub.docker.com/r/tmknom/tfschema/builds/)
[![Docker Automated build](https://img.shields.io/docker/automated/tmknom/tfschema.svg)](https://hub.docker.com/r/tmknom/tfschema/)
[![MicroBadger Size](https://img.shields.io/microbadger/image-size/tmknom/tfschema.svg)](https://microbadger.com/images/tmknom/tfschema)
[![MicroBadger Layers](https://img.shields.io/microbadger/layers/tmknom/tfschema.svg)](https://microbadger.com/images/tmknom/tfschema)
[![License](https://img.shields.io/github/license/tmknom/tfschema.svg)](https://opensource.org/licenses/Apache-2.0)

Dockerfile template.

## Requirements

- [Docker](https://www.docker.com/)

## Usage

```sh
curl -fsSL https://raw.githubusercontent.com/tmknom/tfschema/master/install | sh -s example
cd example
```

## Makefile targets

```text
build                          Build docker image
format                         Format code
help                           Show help
install                        Install requirements
lint                           Lint code
```

## Development

### Installation

```shell
git clone git@github.com:tmknom/tfschema.git
cd tfschema
make install
```

### Deployment

Automatically deployed by "[DockerHub Automated Build](https://docs.docker.com/docker-hub/builds/)" after merge.

### Deployment Pipeline

1. GitHub - Version Control System
   - <https://github.com/tmknom/tfschema>
2. CircleCI - Continuous Integration
   - <https://circleci.com/gh/tmknom/tfschema>
3. Docker Hub - Docker Registry
   - <https://hub.docker.com/r/tmknom/tfschema>
4. MicroBadger - Docker Inspection
   - <https://microbadger.com/images/tmknom/tfschema>

## License

Apache 2 Licensed. See LICENSE for full details.
