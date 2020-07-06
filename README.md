# Hello Go
Simple hello world in `golang` using docker.

# Run
You can either run the `run.sh` file with the command
```
$ sh run.sh
```

Or you can run the commands by yourself.
First, build the image
```
$ docker build --tag hello-from-go .
```

Then execute it
```
$ docker run -it hello-from-go
```

Built with:
- [Docker](https://www.docker.com/): Virtualization tool
- [Golang](https://golang.org/): General purpose programming language
- [Shell script](https://www.shellscript.sh/): Scripting language to simplify the execution steps