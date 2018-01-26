# Nextflow language support in Atom

[![Build Status](https://travis-ci.org/nextflow-io/atom-language-nextflow.svg?branch=master)](https://travis-ci.org/nextflow-io/atom-language-nextflow)

Adds syntax highlighting and snippets to [Nextflow](https://www.nextflow.io) files in Atom.

Originally converted from the [language-groovy](https://github.com/Jakehp/language-groovy) Atom package.

Contributions are *greatly* appreciated. Please fork this repository, open a pull request to add snippets, make grammar tweaks, fix issues, etc.

## Installation

```shell
apm install language-nextflow
```
If `apm` is not recognized, open Atom, open the Atom menu, and select "Install Shell Commands". Then try running the command again.

## Local Development

1. Fork this repository and clone in a local directory. 

2. Use `apm` to link the local copy and install the dependencies:

```shell
apm dev language-nextflow /path/to/your/cloned/fork
```

3. Finally load Atom in development mode: 

```shell
cd ~/.atom/dev/packages/language-nextflow
atom -d
```

The package will appear in the *Development* section of Atom's packages. If you already 
have Atom opened in developer mode and want to reload packages so you can test your changes. 
Just do `cmd-alt-shift-L`. That will refresh Atom.


## Useful links 

* http://flight-manual.atom.io/
* https://www.sitepoint.com/how-to-write-a-syntax-highlighting-package-for-atom/
* http://www.apeth.com/nonblog/stories/textmatebundle.html
* http://manual.macromates.com/en/language_grammars.html#naming_conventions
* https://regex101.com/
