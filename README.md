# Algo Events

## Dev

### Requirements

Some software.

  - `[hugo](https://gohugo.io/getting-started/installing)`
  - `make`
  - `wget`
  - `unzip`

### Once, after cloning

To initialize the theme

	git submodule update --init --recursive

To download necessary static and assets files

	make static assets

### While developping

To build locally

	make build

To serve locally

	make serv

## Deploy

To deploy

	make deploy

Requirements same as dev (see above) + `scp`.
