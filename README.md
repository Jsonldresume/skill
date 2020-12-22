# Skill: JSON-LD Resume Schema
Skill is the name of JSONLD-Schema to define and validate our proposed resume json-ld

[![GitHub Releases](https://badgen.net/github/tag/jsonldresume/skill)](https://github.com/jsonldresume/skill/releases)
[![NPM Release](https://badgen.net/npm/v/jsonldresume)](https://www.npmjs.com/package/jsonldresume)
[![Latest Status](https://github.com/jsonldresume/skill/workflows/Latest/badge.svg)](https://github.com/vanillawc/wc-template/actions)
[![Release Status](https://github.com/jsonldresume/skill/workflows/Release/badge.svg)](https://github.com/vanillawc/wc-template/actions)

Standard, Specification, Schema

### Getting started

```
npm install --save jsonldresume
```

And the JSON-LD Resume schema is available from:

```js
require("resumeldresume").skill;
```
### Contribute

We encourage anyone who's interested in participating in the formation of this standard to join the discussions [here on GitHub](https://github.com/jsonldresume/skill/issues). Also feel free to fork this project and submit new ideas to add to the JSON-LD Resume Schema standard. To make sure all formatting is kept in check, please install the [EditorConfig plugin](http://editorconfig.org/) for your editor of choice.

### Versioning

JSON-LD Resume Schema adheres to Semantic Versioning 2.0.0. If there is a violation of
this scheme, report it as a bug. Specifically, if a patch or minor version is
released and breaks backward compatibility, that version should be immediately
yanked and/or a new version should be immediately released that restores
compatibility. Any change that breaks the public API will only be introduced at
a major-version release. As a result of this policy, you can (and should)
specify any dependency on JSON-LD Resume Schema by using the Pessimistic Version
Constraint with two digits of precision.

We use automatic semver system.

Pull requests titles should be formatted as such

```
"fix: added something" - will bump the patch version
"feat: added something" - will bump the minor version
```

`major` version bumps will be few and far between for this schema.

### Other resume standards

- [HR-XML](https://schemas.liquid-technologies.com/HR-XML/2007-04-15/)
- [Europass](http://europass.cedefop.europa.eu/about-europass)
