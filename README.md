# LevelGraph CLI

A command line interface for working with local LevelGraph databases

## Usage

Currently, there's no code. However, this is what we hope to build here:

```
$ levelgraph {db} # creates a DB with that name OR returns info on the DB
$ levelgraph {db} -s|-p|-o {value} # return triples for some combo of s/p/o
$ levelgraph {db} --import {filename} # import Turlte, N3, or JSON-LD
$ levelgraph {db} --export {filename} --as {format}
```

## License

MIT
