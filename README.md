# create-module-guide

This is the companion repository to the [Create Module guide](https://docs.nullstone.io/extending/guides/create-module).
This contains a working example of a basic Nullstone module.

This module is a `datastore` Nullstone module that creates a private S3 bucket and outputs the bucket information.

## Fork Warning

This repository contains a module manifest at `.nullstone/module.yml` containing the metadata for the Nullstone module.
This is currently registered to the `nullstone` organization in Nullstone.
If you want to fork, make sure to change `org_name` in `.nullstone/module.yml`.
