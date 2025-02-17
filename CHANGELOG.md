Changelog
=========

1.0.1
-----

_2023-02-15_

### Changes

* Add installation instructions to index.md by @ZacSweers in https://github.com/slackhq/compose-lints/pull/44
* Fix possible typo in README by @WhosNickDoglio in https://github.com/slackhq/compose-lints/pull/45
* Hopefully fix publish-docs actions by @chrisbanes in https://github.com/slackhq/compose-lints/pull/47
* Update lint-latest to v31.1.0-alpha04 by @slack-oss-bot in https://github.com/slackhq/compose-lints/pull/51
* Update dependency mkdocs-material to v9.0.12 by @slack-oss-bot in https://github.com/slackhq/compose-lints/pull/50
* Downgrade ComposeCompositionLocalUsage to warning by @chrisbanes in https://github.com/slackhq/compose-lints/pull/52
* Misc mutable parameter fixes by @ZacSweers in https://github.com/slackhq/compose-lints/pull/49
* Update plugin spotless to v6.15.0 by @slack-oss-bot in https://github.com/slackhq/compose-lints/pull/54
* Update dependency gradle to v8 by @slack-oss-bot in https://github.com/slackhq/compose-lints/pull/55
* Update Lint baseline by @chrisbanes in https://github.com/slackhq/compose-lints/pull/58

### New Contributors
* @WhosNickDoglio made their first contribution in https://github.com/slackhq/compose-lints/pull/45

**Full Changelog**: https://github.com/slackhq/compose-lints/compare/1.0.0...1.0.1

1.0.0
-----

_2023-02-09_

Initial release!

This is a near-full port of the original rule set to lint. It should be mostly at parity with the original rules as well.

The lints target lint-api `30.4.0`/lint API `13` and target Java 11.

See the docs for full usage and information: https://slackhq.github.io/compose-lints.

**Notes**
- `ComposeViewModelInjection` does not offer a quickfix yet. PRs welcome!
- `ComposeUnstableCollections` is a warning by default rather than an error.
- `CompositionLocalNaming` is not ported because this is offered in compose's bundled lint rules now.
