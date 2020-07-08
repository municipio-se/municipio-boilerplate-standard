# Contributing to this Municipio boilerplate

Please read this document carefully before contributing to this package.

## Releases and versioning

When making a new release, the version tag should be chosen according to the
principles of [Semantic Versioning](https://semver.org/) with the
MAJOR.MINOR.PATCH pattern. Since this package is a project template and will not
be used as a dependency, the version tag is of less importance, but it works as
an indicator of what kind of changes has been made and if code will be
compatible between different projects. Therefore you should treat this as a
regular library package for the purpose of versioning.

If the new release introduces any breaking changes, the _major_ version number
MUST be increased to prevent consumers from accidentally updating to an
incompatible version of this package. The _minor_ version number is increased
when backwards-compatible features are added. The _patch_ version is increased
only when making backwards-compatible bugfixes and security updates.

When making a new release, don’t forget to also update the version number in the
package.json file and update CHANGELOG.md

## Code formatting

Format all files with Prettier before committing your changes by running
`yarn format`.
