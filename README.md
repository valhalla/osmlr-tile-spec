OSMLR Tile Specification
------------------------

OSMLR is a specification for identifying parts of a road network based on [OpenLR](http://www.openlr.org/). The aim is to identify road network parts useful for traffic segmentation without requiring a particular version of any data source.

Documentation
-------------

The specification is written in [Google Protocol Buffers](https://developers.google.com/protocol-buffers/) syntax, and there are many comments within the files to describe the function and intent of the various parts.

For an introduction to the concepts behind OSMLR, please see the [documentation of the OSMLR software](https://github.com/opentraffic/osmlr/blob/master/docs/intro.md).

Sample Data
-----------

Sample OSMLR tiles are attached to each release of this spec:

- [v1.0.0-rc.1 tiles for Manila, Philippines as PBF](https://github.com/opentraffic/osmlr-tile-spec/releases/download/v1.0.0-rc.1/osmlr_sample_pbf_manila.tar)
- [v1.0.0-rc.1 tiles for Manila, Philippines as GeoJSON](https://github.com/opentraffic/osmlr-tile-spec/releases/download/v1.0.0-rc.1/osmlr_sample_geojson_manila.tar)

License
-------

The specification is released under the MIT License. Please see [LICENSE.md](LICENSE.md) for more information.

Versioning
----------

The specification uses [semantic versioning](http://semver.org/). Released versions of the specification correspond to tags in the form `vMAJOR.MINOR.PATCH`.

Contributing
------------

The OpenTraffic project welcomes contributions! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for more information.
