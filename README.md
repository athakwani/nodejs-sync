This dupper template repository is for Nodejs + Sync development environment.

Nodejs + Sync Development Environment
=====================================

This template install nodejs dependencies and implements sync command that starts bidirectional code sync between repository source code and local directory.  

.. code-block:: bash

  dupper dup -t --name=myrepo --template-from=https://github.com/athakwani/nodejs-sync GITURL
  dupper exec -t myrepo sync DIR
      
Commands
========

* sync
    
.. code-block:: bash

    Usage:
    dupper exec -t CONTAINER sync DIR
    
