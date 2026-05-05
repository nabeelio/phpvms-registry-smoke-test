# phpvms-registry-smoke-test

Disposable fixture addon used to smoke-test the
[phpvms/addon-registry](https://github.com/phpvms/addon-registry) pipeline.

Not a real plugin. Do not install.

## Releasing

Tag a version (e.g. `v0.1.0`), push the tag, then create a GitHub
release that uploads the repo source as a zip asset. The registry
validator hashes that zip and verifies `module.json` lives at the
zip root.
