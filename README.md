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

### Syncing with remote

Fetching and merging last changes:

	git pull

If you are not editing the theme:

	git submodule update --recursive

If you are editing the theme:

	cd themes/events
	git checkout master
	git pull

And once `master` is checked out you can simply replace `git pull` at the root by

	git pull --recurse-submodules

### While developping

To build locally

	make build

To serve locally

	make serv

## Deploy

To deploy

	make deploy

Requirements same as dev (see above) + `scp`.
