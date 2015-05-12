# httpdbaas

This cookbook installs the apache2 package and starts the apache2 service. The purpose of this cookbook is to act as a runtime dependency for the [sitedbaas](https://github.com/binamov/sitedbaas) cookbook.

## supported platforms
This cookbook has been tested on:
* Ubuntu 14.04

## pre-requisites
This cookbook has a dependency on:
* apt cookbook

## Usage
You can just add `recipe[httpdbaas]` to the run_list of your node
