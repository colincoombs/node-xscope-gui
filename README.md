# node-xscope-gui

A HTML-based GUI for my node-xscope project

### Background

The node-xscope project was aimed at producing a driver package for a Gabotronics Xminilab oscilloscope module,
which should be easy to use in small coffeescript scripts run from the command-line.

This project is aimed at producing a GUI framework for using that driver. 
The requirements for such a framework are not yet clear, so I will be learning which features are useful
and which are just silly as I go along.

I do have a particular goal in mind, but I will not describe it here until I have a few diagrams to clarify it.

The GUI will be produced using HTML & co. rather that widget sets like Qt or GTK+, because I want to
~~play with~~ familiarise myself with modern web technologies.

I would expect to base such an application on node-webkit or something similar, 
but I had no success with any of the candidates yet.
The initial development will therefore be in the good old server-plus-client configuration, 
but with the thought that sometime the 'server-side' and 'client-side' parts can be brought
together into a single executable.

### Current Status

Nothing exists just yet, just a load of ideas in my head and a bunch of other open-source projects
which are showing me a possible way to build them.

