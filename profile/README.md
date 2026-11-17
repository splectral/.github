# SPLectral

Components for SPLectral, the platform for seeing and working with running
systems in the browser. The components work in SPLectral's own abstract world
(hosts, nodes, resources named by URI, and their activity) and know nothing of
what runs underneath.

Its first step on the current platform is one page: an install shown as a
tree, its commands appearing as they complete. It is a package in
**[HAICCing](https://github.com/haiccing)**, `base-package-splectral`, on
the server `splectral-server` in
[pear-full-square](https://github.com/pear-full-square), where SPLectral's
engine lives. The repositories here, a map view and the two demos' scenarios,
are of the earlier platform and rest; the components come back as the
platform needs them.

## The five organisations

SPLectrum's engineering is spread over five GitHub organisations:

- **[splectrum](https://github.com/splectrum)**: where SPLectrum, the
  philosophy project, lives, and where its engineering is planned.
- **[bare-for-pear](https://github.com/bare-for-pear)**: outside code
  changed to run on Bare. It rests until the platform needs it.
- **[pear-full-square](https://github.com/pear-full-square)**: the engines,
  all of the platform's code, one module a repository.
- **[HAICCing](https://github.com/haiccing)**: the packages made from those
  modules, and the `haicc` command: what you can run. Start here.
- **[SPLectral](https://github.com/splectral)** (this one): components for seeing and
  working with running systems in the browser.

Part of the engineering of [SPLectrum](https://splectrum.world).
