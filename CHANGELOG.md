# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).


## [Unreleased]
### Added
 - Introducing `util.Any(*types)` and `util.Optional(value)` meta-values to allow flexibility when performing equality comparisons.
 - Added `util.Collection`, `util.List`, and `util.Set` to flexibly perform assertions on collection types when performing equality comparisons.


## [0.0.1] — 2019-08-14
### Added
 - Introducing `assert_dict_is_subset` and `assert_model_attrs` assertion utilities