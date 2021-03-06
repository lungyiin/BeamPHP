# BeamPHP [![Packagist badge](https://img.shields.io/packagist/v/tama63/beam.svg?style=flat-square)](https://packagist.org/packages/tama63/beam)
WIP Beam API Library for PHP

## Installing
Via composer: 

`composer require tama63/beam`

## Usage
A relevant class has been created for most of the non-auth endpoints on https://developer.beam.pro/api/endpoints, additionally the parameters of each method also use those defined in the end point. 

Current endpoints that have been included are as follows:
* User($userID)
* Users()
* Channel($channelID)
* Channels()
* Achievements()
* Shop()
* Chat($chatID)

The classes can be initialised by calling (for example):

`$beamUser = new \Tama63\Beam\User($userID);`

## Generating documentation
* Uses https://github.com/evert/phpdoc-md to generate the documentation

## Todo
* Tests
* Finish other endpoints
