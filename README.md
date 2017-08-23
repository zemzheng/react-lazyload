# react-lazyload2

* [![Build Status](https://travis-ci.org/zemzheng/react-lazyload2.svg)](https://travis-ci.org/zemzheng/react-lazyload2)
* [![npm version](https://badge.fury.io/js/react-lazyload2.svg)](http://badge.fury.io/js/react-lazyload2)
* [![Coverage Status](https://coveralls.io/repos/github/zemzheng/react-lazyload2/badge.svg?branch=master)](https://coveralls.io/github/zemzheng/react-lazyload2?branch=master)
* [![npm downloads](https://img.shields.io/npm/dm/react-lazyload2.svg)](https://www.npmjs.com/package/react-lazyload2)

`Hey, jasonslyvia. Too late to updated and fix my issue. So I Publish an version 2.`

[Fork from react-lazyload](https://github.com/jasonslyvia/react-lazyload)

## what's different?

* fix [84](https://github.com/jasonslyvia/react-lazyload/issues/84)
* fix [97](https://github.com/jasonslyvia/react-lazyload/issues/97)
* add props target
```
// target : oneOf([
//     React.PropTypes.func, // which return an html dom
//     React.PropTypes.node, // html dom
// ])
// bind the target scroll event
<LazyLoad ... target={ ... }/>
```
