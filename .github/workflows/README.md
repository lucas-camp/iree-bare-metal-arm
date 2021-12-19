# GitHub CI

This folder contains continuous integration workflows.

The workflow `build-and-test.yml` uses artifacts to share built targets between build and test job. As GitHub does not provide a builtin action for deleting an artifact, we use a third party [`delete-artifact`](https://github.com/GeekyEggo/delete-artifact) action.