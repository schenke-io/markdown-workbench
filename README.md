<!--

This file was written by 'MakeMarkdown.php' line 21 using
SchenkeIo\PackagingTools\Markdown\MarkdownAssembler

Do not edit manually as it will be overwritten.

-->

# Packaging Tools

[![Latest Version on Packagist](https://img.shields.io/packagist/v/schenke-io/packaging-tools?style=plastic)](https://packagist.org/packages/schenke-io/packaging-tools)
[![GitHub Tests Action Status](https://img.shields.io/github/actions/workflow/status/schenke-io/packaging-tools/run-tests.yml?branch=main&label=tests&style=plastic)](https://github.com/schenke-io/packaging-tools/actions?query=workflow%3Arun-tests+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/schenke-io/packaging-tools.svg?style=plastic)](https://packagist.org/packages/schenke-io/packaging-tools)
![](/.github/coverage-badge.svg)
![](/.github/phpstan.svg)


![](/.github/werkstatt.png)

This package is a collection of tools to simplify the package and project development.

The main elements are:
- **Markdown** Assemble the readme.md file out of small markdown files, class comments and other sources
- **Badge** build the badge custom or from coverage logfiles



* [Packaging Tools](#packaging-tools)
  * [Installation](#installation)




## Installation

Install the package with composer:

```bash
  composer require schenke-io/packaging-tools
```

Add the setup command into `composer.json` under scripts.

```json
{
    
    
    "scripts": {
        "setup": "SchenkeIo\\PackagingTools\\Setup::handle"    
    }
    
}

```



Start the setup:

```bash
  composer setup
```

and check all available commands:

```bash
  composer setup help
```




