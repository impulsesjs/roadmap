# Impulses.js Roadmap

## Core

### 0.1
* **Lead:** @joaocac
* Vulnerabilities removed from the code
* Documentation updates with all shields and main information
* Documentation for the base elements composing the library
* Documentation for the general function
* Base functionality
* Base functionality unit tests

### 1.0
* **Lead:** @joaocac
* Channel Documentation
* BUS Documentation
* Documentation site for the first version
* Examples on how to use the library

### 1.1
* **Lead:** @joaocac
* API class to be used by any entity
* Documentation for the API
* Update Documentation site
* Extra examples on how to use the API

### 1.2
* **Lead:** @joaocac
* API as a base Class (to be extended)
* Documentation for the API inheritance mode
* Update Documentation site
* Extra examples on how to use the API

### 2.0-b
* **Lead:** @joaocac
* Allow the system to be also loaded into a web worker (PoC)
* Creation of script for communication with the worker (PoC)
* Documentation explaining the changes
* Update Documentation site (PoC)
* Extra examples on how to use the WebWorker feature (PoC)

### Backlog
* Integration tests for several scenarios
* Allow it to run as a separated thread to prevent blocking the UI (with or without Framework)
* Generate and maintaining an Event Based API for each entity. 
* Simple integration (not requiring to change current code)
* Ease of usage for the developer (API).
* Major Framework integration plugins
* Protective mode by preventing duplication of listener registration
* Sanity and Cleaning service for the non existing listener
* Message queuing
* Overall Communication status control system
* Event journey and traceability (local and remote)
* Integration plugin architecture for connection with outside world
* Integration plugin to work with [deepstreamHub](https://deepstreamhub.com/)
* Integration plugin to work with [SocketCluster](https://socketcluster.io/)
* Integration plugin to work with [rethinkDB](https://www.rethinkdb.com/)
* Integration plugin to work with [Firebase](https://firebase.google.com/)
* Integration plugin for Vue
* Integration plugin for React
* Integration plugin for Angular
* Very small footprint
