# learning_go

## Commands: 
* go run <filename.go>  //where filename.go has package main and func main
* go build
* ~/GolandProjects/learning_go$ go build
  go: cannot find main module, but found .git/config in /home/mykola/GolandProjects/learning_go
  to create a module there, run:
  go mod init

There are packages and modules. 1 module can have many packages
Simply, a module is a go project

~/GolandProjects/learning_go$ go mod init
go: cannot determine module path for source directory /home/mykola/GolandProjects/learning_go (outside GOPATH, module path must be specified)

Example usage:
'go mod init example.com/m' to initialize a v0 or v1 module
'go mod init example.com/m/v2' to initialize a v2 module

Run 'go help mod init' for more information.

# go mod init github.com/nikolaynest/learning_go
It creates file with module name: "learning_go"

To run executable file: 
# ./learning_go
Now can we share our application with other, without installing Go on clients side.

# To run go file: 
go run investment_calculator.go

# To run go module (it should have go.mod file) 
go run .

