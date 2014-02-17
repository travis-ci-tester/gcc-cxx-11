`gcc.default` (**failed**: by default no c++11 support):
[![Build Status](https://travis-ci.org/travis-ci-tester/travis-test-gcc-cxx-11.png?branch=gcc.default)][repo]

`try.install.gcc-4.8` (**failed**: no such package):
[![Build Status](https://travis-ci.org/travis-ci-tester/travis-test-gcc-cxx-11.png?branch=try.install.gcc-4.8)][repo]

`install.from.external` (**passed**):
[![Build Status](https://travis-ci.org/travis-ci-tester/travis-test-gcc-cxx-11.png?branch=install.from.external)][repo]

`install.from.external.i386` (**failed**): [![Build Status][install.from.external.i386]][repo]

[repo]: https://travis-ci.org/travis-ci-tester/travis-test-gcc-cxx-11
[install.from.external.i386]: https://travis-ci.org/travis-ci-tester/travis-test-gcc-cxx-11.png?branch=install.from.external.i386

### Notes
* cmake toolchain: https://github.com/ruslo/polly#gcc48
