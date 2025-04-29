# Learning Go by Jon Bodner

## Install Go in Ubuntu

```bash
# Download and extract Go
tar -C /usr/local -xzf go1.20.5.linux-amd64.tar.gz

# Add Go to PATH
echo 'export PATH=$PATH:/usr/local/go/bin' >> $HOME/.bash_profile
source $HOME/.bash_profile
```

## Check Go Version
```aiignore
go version
```

## Go Tooling
1. go build — Compiles Go code to executable binaries
2. go fmt — Automatically formats Go source code
3. go mod — Manages modules and dependencies
4. go test — Runs tests
5. go vet — Performs static analysis to find mistakes

## Initialize a new Go module
```aiignore
go mod init hello_world
```
## Build executable
```aiignore
go build
```

## Format the code
```aiignore
go fmt ./...
```

## Run static analysis
```aiignore
go vet ./...
```

