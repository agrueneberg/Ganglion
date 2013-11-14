Ganglion
========

A script loader for browser-based software ecosystems.


Example
-------

    // Load module.
    ganglion.loadModule("http://code.jquery.com/jquery-latest.min.js");

    // Print a list of loaded modules.
    ganglion.registry.list(function (err, modules) {
        console.log(modules);
    });
