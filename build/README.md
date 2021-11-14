# `build/`

This directory is not required, but its name should be reserved.

The `build/` directory is special in that it must not be committed to a source
control system. A user downloading the codebase should not see a `build/`
directory present in the project root, but one may be created in the course of
working with the software. The `_build/` directory is also reserved.

> Note: Some build systems may commandeer the `build/` directory for themselves.
In this case, the directory `_build/` should be used in place of `build/`.

The `build/` directory may be used for ephemeral build results. Other uses of
the directory are not permitted.

Creation of additional directories for build results in the root directory is
not permitted.

> Note: Although multiple *root* directories are not allowed, the structure and
layout of the `build/` directory is not prescribed. Multiple subdirectories of
`build/` may be used to hold multiple build results of different configuration.