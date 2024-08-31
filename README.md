# Teaching Empirical Research Methods in Software Engineering

## Build and Run

Prerequisite: [install Hugo](https://gohugo.io/installation/).

Clone the repository and initiate the git submodule needed for the used theme.

```sh
git clone git@github.com:mendezfe/temse.git
cd temse 
git submodule update --init
```

You can then start the Hugo server.

```sh
hugo serve -D
```

The web server is then available at [http://localhost:1313/](http://localhost:1313/).
