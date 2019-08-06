# FINOS Reference FOSS Policy for Financial Services Institutions

## Overview

This is a template for a comprehensive free and open source software (FOSS) policy for a financial services institution, including sample provisions governing the acquisition and use of FOSS, and contribution to FOSS projects.

The policy is available [in Asciidoc format](/src/FINOS-reference-FOSS-policy.adoc) for easier changes and collaboration.

## Disclaimer

This Reference FOSS Policy is offered only as a reference, not as a complete policy or as legal advice. While this policy has been drafted to be generally applicable, it does not define every implementation detail. Every company's policy should be customized to its particular needs, policy and technical environments, and risk tolerance.

## Installing

The template source document is written in [AsciiDoc](http://asciidoc.org/),
a powerful but still lightweight markup language.
Think of it as a super-set of markdown with minor syntactic differences.

A popular IDE is [AsciidocFX](https://asciidocfx.com/),
although most code editors support the format.

### Asciidoc toolchain

There are many to choose from,
but we suggest the Ruby gem [asciidoctor](https://asciidoctor.org/).

To install on a mac, using homebrew:

```
$ brew install asciidoctor
```

### Pandoc

To support many output formats, including Word documents,
you may use [Pandoc](https://pandoc.org/),
a universal document converter.

To install on a mac, using homebrew:

```
$ brew install pandoc
```

## Using

To output this document in Word format:

```
$ asciidoctor -b docbook5 FINOS-reference-FOSS-policy.adoc | pandoc -s -f docbook -t docx -o your-filename.docx
```

Many other outputs are available via `pandoc`.

To output in HTML (the default):

```
$ asciidoctor FINOS-reference-FOSS-policy.adoc
```

Many styling options exist in this rich toolchain, including CSS.

## Copyright

© 2017 Fintech Open Source Foundation. This document is licensed under the terms of the Creative Commons Attribution (CC By) License, version 4.0 (https://creativecommons.org/licenses/by/4.0/). It is offered as-is and as-available, without representation or warranty of any kind, whether express, implied, statutory, or other. The original version of this document is available at https://github.com/finos-osr/reference-foss-policy. Any modified version must indicate modifications. This notice and disclaimer must be retained on any copies and derivative works.

## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Read our [contribution guidelines](.github/CONTRIBUTING.md) and [Community Code of Conduct](https://www.finos.org/code-of-conduct)
4. Commit your changes (`git commit -am 'Add some fooBar'`)
5. Push to the branch (`git push origin feature/fooBar`)
6. Create a new Pull Request

_NOTE:_ Commits and pull requests to FINOS repositories will only be accepted from those contributors with an active, executed Individual Contributor License Agreement (ICLA) with FINOS OR who are covered under an existing and active Corporate Contribution License Agreement (CCLA) executed with FINOS. Commits from individuals not covered under an ICLA or CCLA will be flagged and blocked by the FINOS Clabot tool. Please note that some CCLAs require individuals/employees to be explicitly named on the CCLA.

*Need an ICLA? Unsure if you are covered under an existing CCLA? Email [help@finos.org](mailto:help@finos.org)*


## License

Copyright 2019 - FINOS

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
