[@aureooms/js-codec-base32](https://make-github-pseudonymous-again.github.io/js-codec-base32)
==

Base32 encoder/decoder for JavaScript.
See [docs](https://make-github-pseudonymous-again.github.io/js-codec-base32/index.html).
Parent is [@aureooms/js-codec](https://github.com/make-github-pseudonymous-again/js-codec).

```js
> import ascii from '@aureooms/js-codec-ascii' ;
> import base32 from '@aureooms/js-codec-base32' ;
> let bytes = ascii.encode('Hello!') ;
> base32.decode( bytes ) ;
'JBSWY3DPEE======'
> base32.decode( bytes , { variant : 'base32hex' } ) ;
'91IMOR3F44======'
> base32.decode( bytes , { variant : 'z-base-32' } ) ;
'jb1sa5dxrr'
> base32.decode( bytes , { variant : 'crockford' } ) ;
'91JPRV3F44'
> base32.decode( bytes , { alphabet : 'BCDEFGHIJKLMNOPQRSTUVWXYZ234567A' , padding : '.' } ) ;
'KCTXZ4EQFF......'
```

[![License](https://img.shields.io/github/license/make-github-pseudonymous-again/js-codec-base32.svg)](https://raw.githubusercontent.com/make-github-pseudonymous-again/js-codec-base32/main/LICENSE)
[![Version](https://img.shields.io/npm/v/@aureooms/js-codec-base32.svg)](https://www.npmjs.org/package/@aureooms/js-codec-base32)
[![Build](https://img.shields.io/travis/make-github-pseudonymous-again/js-codec-base32/main.svg)](https://travis-ci.org/make-github-pseudonymous-again/js-codec-base32/branches)
[![Dependencies](https://img.shields.io/david/make-github-pseudonymous-again/js-codec-base32.svg)](https://david-dm.org/make-github-pseudonymous-again/js-codec-base32)
[![Dev dependencies](https://img.shields.io/david/dev/make-github-pseudonymous-again/js-codec-base32.svg)](https://david-dm.org/make-github-pseudonymous-again/js-codec-base32?type=dev)
[![GitHub issues](https://img.shields.io/github/issues/make-github-pseudonymous-again/js-codec-base32.svg)](https://github.com/make-github-pseudonymous-again/js-codec-base32/issues)
[![Downloads](https://img.shields.io/npm/dm/@aureooms/js-codec-base32.svg)](https://www.npmjs.org/package/@aureooms/js-codec-base32)

[![Code issues](https://img.shields.io/codeclimate/issues/make-github-pseudonymous-again/js-codec-base32.svg)](https://codeclimate.com/github/make-github-pseudonymous-again/js-codec-base32/issues)
[![Code maintainability](https://img.shields.io/codeclimate/maintainability/make-github-pseudonymous-again/js-codec-base32.svg)](https://codeclimate.com/github/make-github-pseudonymous-again/js-codec-base32/trends/churn)
[![Code coverage (cov)](https://img.shields.io/codecov/c/gh/make-github-pseudonymous-again/js-codec-base32/main.svg)](https://codecov.io/gh/make-github-pseudonymous-again/js-codec-base32)
[![Code technical debt](https://img.shields.io/codeclimate/tech-debt/make-github-pseudonymous-again/js-codec-base32.svg)](https://codeclimate.com/github/make-github-pseudonymous-again/js-codec-base32/trends/technical_debt)
[![Documentation](https://make-github-pseudonymous-again.github.io/js-codec-base32/badge.svg)](https://make-github-pseudonymous-again.github.io/js-codec-base32/source.html)
[![Package size](https://img.shields.io/bundlephobia/minzip/@aureooms/js-codec-base32)](https://bundlephobia.com/result?p=@aureooms/js-codec-base32)
