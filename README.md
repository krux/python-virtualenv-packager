# ve-packager
A wrapper for fpm to create packages from Python virtual environments.

Based on a shell script by @plathrop. The use case is pretty environment-specific, but I've tried to keep it agnostic.

## Usage

Ideally, cd to the root of your checked-out repo, and run it:

    $ cd my-python-project
    $ ve-packager