docker-node
===========

WHAT IS THIS?
-------------

Docker images for node using `resnullius/alpine:latest` for `lts` and `stable`.

Expect:

- `resnullius/docker:lts`
- `resnullius/docker:lts-build`
- `resnullius/docker:stable`
- `resnullius/docker:stable-build`

The `-build` means it has the packages for building C++ addons; the non `-build`
is smaller but can only install native modules.

AUTHOR AND LICENSE
------------------
© 2016, Jose-Luis Rivas `<me@ghostbar.co>`.

This software is licensed under the MIT terms, you can find a copy of the
license on the `LICENSE` file in this repository.
