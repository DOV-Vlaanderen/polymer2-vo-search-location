# \<vo-search-location\>

Find lat-long location for an address using the [AGIV Geolocation API](https://loc.geopunt.be/).

![example](https://github.com/DOV-Vlaanderen/polymer2-vo-search-location/blob/assets/assets/images/vo-search-crab.png?raw=true)

Example:

```html
    <vo-search-location
        latitude="{{latitude}}"
        longitude="{{longitude}}"
        focus="true">
    </vo-search-location>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```
An initial test is added but it should be improved.

Todo: the test should use a stubbed crab service. The test relies to much on the internal structure of the vaadin combo box.
Todo: add a test to check the event when an item is selected in the combox

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
