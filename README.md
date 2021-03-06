# gca

Graph Classical Algorithms: Use classic algorithms like BFS and Edmonds Krap on graphs.

## Installation

```bash
npm i gca
```

## Usage

```js
const gca = require('gca');
const tool = new gca();

let graph = tool.CreateGraph();
graph.addNode(1);
graph.addNode(2);
graph.addEdge(1, 2);
let bfsGraph = tool.BFS(graph, 1);
let flowGraph = tool.CreateFlowGraph();
flowGraph.addEdge(flowGraph.s, flowGraph.t);
let maxFlow = tool.EdmondsKarp(flowGraph);
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## API

Full documentation can be found [here](https://amirlib.github.io/gca/#/).

A changelog file can be found [here](https://github.com/amirlib/gca/blob/master/CHANELOG.md).

Also, there an [example.js](https://github.com/amirlib/gca/blob/master/example.js) page.

## Author

### Amir Liberzon

[LinkedIn Profile](https://www.linkedin.com/in/amir-liberzon-23aa3a159/)  
[Github Profile](https://github.com/amirlib/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/babudabu/gca/blob/master/LICENSE) file for details.
