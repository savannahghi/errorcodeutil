[![Maintained](https://img.shields.io/badge/Maintained-Actively-informational.svg?style=for-the-badge)](https://shields.io/) 

[![MIT license](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)  ![Linting and Tests](https://github.com/savannahghi/errorcodeutil/actions/workflows/ci.yml/badge.svg)  [![Coverage Status](https://coveralls.io/repos/github/savannahghi/errorcodeutil/badge.svg?branch=main)](https://coveralls.io/github/savannahghi/errorcodeutil?branch=main)

# Error Code Util
`errorcodeutil` is a utils package that has constants that define different types of errors 

### Installing it
errorcodeutil is compatible with modern Go releases in module mode, with Go installed:

```bash
go get -u github.com/savannahghi/errorcodeutil

```
will resolve and add the package to the current development module.

Alternatively the same can be achieved if you use import in a package:

```go
import "github.com/savannahghi/errorcodeutil"

```
and run `go get` without parameters.

The package name is `errorcodeutil`


### Developing

The default branch library is `main`

We try to follow semantic versioning ( <https://semver.org/> ). For that reason,
every major, minor and point release should be _tagged_.

```
git tag -m "v0.0.1" "v0.0.1"
git push --tags
```

## Contributing ##
I would like to cover the entire GitHub API and contributions are of course always welcome. The
calling pattern is pretty well established, so adding new methods is relatively
straightforward. See [`CONTRIBUTING.md`](CONTRIBUTING.md) for details.

## Versioning ##

In general, errorcodeutil follows [semver](https://semver.org/) as closely as we
can for tagging releases of the package. For self-contained libraries, the
application of semantic versioning is relatively straightforward and generally
understood. We've adopted the following
versioning policy:

* We increment the **major version** with any incompatible change to
	non-preview functionality, including changes to the exported Go API surface
	or behavior of the API.
* We increment the **minor version** with any backwards-compatible changes to
	functionality, as well as any changes to preview functionality in the GitHub
	API. GitHub makes no guarantee about the stability of preview functionality,
	so neither do we consider it a stable part of the go-github API.
* We increment the **patch version** with any backwards-compatible bug fixes.

## License ##

This library is distributed under the MIT license found in the [LICENSE](./LICENSE)
file.