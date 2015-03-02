# devbox-docker

Development environments in docker containers, for rationale see [blogpost](http://martintrojer.github.io/software/2015/02/22/moving-my-devboxes-to-docker/).

## Hybrid

A golang development environment, where your editor/IDE is outside the container, and the source folders is shared.

## All-in

A multi-user, java (remove) development environment with editor built-in. Has support for screen-sharing (wemux).

## Usage

Docker (>=1.5.0)

`$ ./build-all.sh` to build the containters.

`$ ./connect-local.sh` to launch a bash shell in local container.

`$ ./run-remove.sh` to run the 'remove' container, use ssh to connect.
