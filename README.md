# Infinity Framwork 

Language : GoLang
Version : go1.12.1

For Most of Application, We prefer to use GO Core for BackEnd Implementation and React(Mostly)or Angular for FrontEnd Implementation  


##### It is necessary that the code should be placed in $GOPATH/src/github.com/ folder.


## Architecture of Golang (Backend)

Application is made up of following main Entities/ Layers :
#### API ####
  [X] handles: Request handler 
  [X] Middleware: connects network-based requests generated by a user to the back-end data the end user is requesting 
  [X] model: has aggregate, entity and value object
  [X] repository: has repository interfaces of aggregate
  [X] services: Has application services that depend on several models
#### configs : All configation informance are present
#### database : database model functioanlity
#### log : all dailybasis log store here
#### vendor: for external packages


```
$ ./bin/setup
```

## Run

```
$ ./bin/parking_lot <File_Name>
```


## Test

```
$ go test ./...
```


