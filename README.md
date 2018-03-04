# arch-python

My basic Archlinux Image with a working python environment.

## Build it

Just run: `make`

## Verify it

Just run: `make bash`

Now you can verify that it build correctly.

## Publish it (manually)

This should not be necessary because a build is triggered on Docker Hub if you push to `master`.
But if you need to do it you can.

Just run: `make publish VERSION=<version>`
