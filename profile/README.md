# SPLectral

Interaction: the packages whose concern is how people and other systems
work with a running system, first of all the UI in a browser. SPLectral is
a platform for components; each component is an app it installs and
serves. The components work in SPLectral's own abstract world (hosts,
nodes, resources named by URI, and their activity) and know nothing of
what runs underneath.

The platform itself is a package in **[HAICCing](https://github.com/haiccing)**,
`base-package-splectral`, on the server `splectral-server` in
[pear-full-square](https://github.com/pear-full-square), where SPLectral's
engine lives. It shows an install as a tree, its commands appearing as
they complete. Its first component, the info viewer (the platform's
documentation read in a browser as the command line reads it), is a proof
of concept and comes here when it is published. The repositories here now,
a map view and the two demos' scenarios, are of the earlier platform and
rest.

## The seven organisations

SPLectrum's engineering is spread over seven GitHub organisations:

- **[splectrum](https://github.com/splectrum)**: where SPLectrum, the
  philosophy project, lives, and where its engineering is planned.
- **[bare-for-pear](https://github.com/bare-for-pear)**: outside code
  changed to run on Bare. It rests until the platform needs it.
- **[pear-full-square](https://github.com/pear-full-square)**: the engines,
  all of the platform's code, one module a repository.
- **[HAICCing](https://github.com/haiccing)**: the packages made from those
  modules, and the `haicc` command: what you can run. Start here.
- **[myctral](https://github.com/myctral)**: mycelium's data
  repositories: state.
- **[myctrans](https://github.com/myctrans)**: data transformation:
  process.
- **[SPLectral](https://github.com/splectral)** (this one): interaction, first of
  all the UI.

Part of the engineering of [SPLectrum](https://splectrum.world).
