Building jQuery UI for AMD (RequireJS)
======================================

Out of the box jQuery UI is not AMD capable. It can either be used as whole or in form of a custom build that
is a fixed set of jQuery UI controls during runtime. To be able to only include what's needed during runtime,
we used a node module that translates all jQuery UI files to AMD modules. Thus all dependencies are resolved
automatically and kept as small as possible.

Link to the node module: https://github.com/jrburke/jqueryui-amd

