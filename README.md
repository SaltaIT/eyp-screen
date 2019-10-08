# screen

#### Table of Contents

1. [Overview](#overview)
2. [Module Description](#module-description)
3. [Setup](#setup)
    * [What screen affects](#what-screen-affects)
    * [Setup requirements](#setup-requirements)
    * [Beginning with screen](#beginning-with-screen)
4. [Usage](#usage)
5. [Reference](#reference)
5. [Limitations](#limitations)
6. [Development](#development)

## Overview

Installs screen package.

## Setup

### What screen affects

* Installs screen package.
* Controls /etc/screenrc, it will be overwritten.

### Beginning with screen

Example of the standard configuration:
```puppet
class screen {
  ensure  => 'installed',
}
```

## Usage

* ensure: sets if the package will be installed or erased.

## Reference

Classes:
* screen: main class, installs the module and configures it.

## Limitations

* Debian derivatives: supported.
* Redhat derivatives: supported.
* Other: unsupported.
