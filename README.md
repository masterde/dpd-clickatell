# dpd-clickatell

## Description

Send SMS via Clickatell. You should create your account in Clickatell first.

## Getting started
This module requires deployd ~0.7.0.

If you haven't used Deployd before, make sure to read the [documentation](http://docs.deployd.com/).

### Installation without package.json
````
npm install dpd-clickatell
````

### Installation with package.json
If you have a package.json, you'll have to add this module in it.
````
npm install dpd-clickatell --save
````
Once it is installed, Deployd will automatically load it.  
For more information about Modules, take a look at [the module page on the deployd documentation](http://docs.deployd.com/docs/using-modules/).

## The dpd-clickatell module
### Overview

It is a simple [clickatell](https://www.npmjs.org/package/clickatell-node) wrapper for deployd

### Options/Settings

Require:
 - clickatellUsername
 - clickatellPassword
 - clickatellApiId

 Optional:
 - extra

Please fill them in using the deployd dashboard config page of this module.


### Usage example

    // send a SMS to +123456789
    dpd.clickatell.post({to:'+123456789', body:'Hello World!'});

## Contributing

Just send me a Pull Request in Github.

## Release history

 - 0.1.0: first version

## Contributors

[Eric Fong](https://github.com/ericfong)
[Chris Brand](http://www.cainsvault.com/)
