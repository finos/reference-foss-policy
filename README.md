[![FINOS - Archived](https://cdn.jsdelivr.net/gh/finos/contrib-toolbox@master/images/badge-archived.svg)](https://community.finos.org/docs/governance/Software-Projects/stages/archived)

This project is archived, which means that it's in read-only state; you can download and use this code, but please be aware that it may be buggy and may also contain security vulnerabilities. If you're interested in restoring development activities on this project, please email help@finos.org. 

Please visit https://osr.finos.org/ for updated content.

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
