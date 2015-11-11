[![Build Status](https://travis-ci.org/zzarcon/ember-cli-Mutation-Observer.svg)](https://travis-ci.org/zzarcon/ember-cli-Mutation-Observer)
[![Ember Observer Score](http://emberobserver.com/badges/ember-cli-mutation-observer.svg)](http://emberobserver.com/addons/ember-cli-mutation-observer)

# ember-cli-Mutation-Observer 

> The easiest to subscribe to Dom changes in your ember components

A lightweight ember addon that provides a event based solution for react when the DOM of your components change. It uses [MutationObserver](https://developer.mozilla.org/en/docs/Web/API/MutationObserver) to make magic happen.

## Installation

Ember Cli Mutation Observer works in Ember **1.13.9+** or **2.0+**, including beta and canary, with no deprecations
whatsoever.


As any other ember-cli addon, run:
```
ember install ember-cli-mutation-observer
```

## Using it as a Mixin


## Use it in all your components

If you want to have the functionality available in all your components just set the `mutationObserverInjection` flag to `true` in your `environment`. 

Check [this environment example](https://github.com/zzarcon/ember-cli-Mutation-Observer/blob/master/tests/dummy/config/environment.js#L9)


## Browser support

http://caniuse.com/#feat=mutationobserver
