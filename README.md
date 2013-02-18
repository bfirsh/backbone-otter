backbone-otter
==============

Tools for writing [Otter](https://github.com/bfirsh/otter) apps with [Backbone](http://backbonejs.org).

It currenly provides `BackboneOtter.Model` and `BackboneOtter.Collection`. When models and collections that extend these classes are fetched on an Otter server, it caches the results in `window.otter.cache`. Then, when the client fetches from the same URL, it reads from the cache instead of the server.

This is still a work in progress. More flexible caching and tools for rendering and reinstantiating views is planned.

