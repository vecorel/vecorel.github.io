---
layout: home
title: Vecorel
---

## About Vecorel

The Vector Core Language (Vecorel) project is focused on making any kind of vector data (i.e. geospatial geometries with additional properties) openly available in a unified format on a global scale. We believe that the Vecorel specification is a foundational aspect of vector data interoperability which enables and accelerates additional layers of collaboration and detail via custom extensions.

Vecorel represents a generalization of specialized geospatial data formats, providing a comprehensive framework for describing diverse types of vector data beyond specific domains. The initiative fosters collaboration between academia, industry, NGOs, and governmental organizations toward creating shared global vector datasets that can be used across multiple domains and applications.

## Key Features

The Vecorel specification represents vector data in any kind of vector file format (currently GeoJSON & GeoParquet) in a standard way, with several optional extensions that specify additional attributes. The core data schema of Vecorel is quite simple - it is a set of definitions for attribute names and values. The number of attributes in the core is quite small by design. The idea is that most of the 'interesting' data about the vector features will be located in extensions.

There will likely be lots of different types of extensions: some that are generally accepted as the main way to do things in Vecorel and widely understood by tools and others that are very niche and not widely used but valuable to a small number of users (e.g. an extension specific to a company or organization to help them better validate their data).

You can learn more about the technologies behind the Vecorel specification, read the full specification text, and explore available open data sets and extensions at the links below.

- [The Specification](https://github.com/vecorel/specification)
- [Extensions](extensions/)
- [Software / Tooling](software/)
- [Schema Definition Language (SDL)](https://github.com/vecorel/sdl)

## Community

The Vecorel community strives to provide a welcoming and transparent environment for all of the project's participants. Please read our [Code of Conduct](CODE_OF_CONDUCT.md) for more information.

The Vecorel community has a number of communication channels available for discussion and collaboration.

- Open Discussions and issue trackers for specific topics:
  - [Specification related issues](https://github.com/vecorel/specification/issues)
  - [Discussions forum for anything related to Vecorel](https://github.com/orgs/vecorel/discussions)
  - Issues around specific tooling or extensions go into the [corresponding repositories](https://github.com/orgs/vecorel/repositories)
