*Short changelog - for all the details look at the git log.*

vNEXT, IN PROGRESS
* Add `-dry-run` [#22](https://github.com/rfjakob/cshatag/issues/22)

v2.0, 2020-11-15
* Rewrite cshatag in Go
* add MacOS support
* Add `-remove` flag
* Add `-q` and `-qq` flags
* Accept multiple files per invocation to improve performance
* Work around problems on MacOS SMB mounts
  ([#11](https://github.com/rfjakob/cshatag/pull/11))

v1.1, 2019-06-09
* Add test suite (`make test`)
  ([commit](https://github.com/rfjakob/cshatag/commit/74496854e5c934b6809e816b9e854c5c6585a0f4))
* Add Travis CI
* Drop useless trailing null byte from `user.shatag.sha256`

v1.0, 2019-01-02
* Add `make format` target

2019-02-01
* Fix missing null termination in ts buffer that could lead
  to false positives
  ([commit](https://github.com/rfjakob/cshatag/commit/26873dd71656730d5744efb7fa595d529b3c9ae6))

2017-05-04
* Respect `PREFIX` for `make install`
  ([commit](https://github.com/rfjakob/cshatag/commit/8d1225aabb7bdd3750f161133931b1c456bc2fdb))

2016-09-17
* Check for malloc returning NULL
  ([commit](https://github.com/rfjakob/cshatag/commit/ecadbddffb5e23811a9ae4a5265c287d5ae5c151))

2012-12-05
* C source code & man page published on Github
  ([commit](https://github.com/rfjakob/cshatag/commit/5ce7674ea3210fd0bb6b06a81ca8823e0664761a))
