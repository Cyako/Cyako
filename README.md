# Cyako

The Cyako project is a web framework including both frontend and backend part based on websocket that aims on simple services' realization for small projects.

Currently, library Cyako.js and Cyako.js is provided under development(early stage).

In this stage, easy API and quick service realization are focal points. Features like using memory maps to replace database(with deactivation), using json files to provide and store data that not recommended for large-scaled systems are intended.


###Frontend

[Cyako.js](https://github.com/Cyako/Cyako.js)

Provide fetch(like ES6 fetch API) and listen(for realtime functions) API to communicate with cyako backends.

###Backend

[Cyako.go](https://github.com/Cyako/Cyako.go)

A Cyako backend realization in Go. Provide service auto injections and full-management on processes. For the projects' aim, you don't need to consider of HTTP but to deal with the transactions simply.

[Examples](https://github.com/Cyako/example) are also provided in the repository. Now is for test.
