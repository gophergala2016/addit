# addit

Interactive tool for Go application development.

## Note: Development in progress. Performance may not be satisfactory.

### Getting started
#### 1. Install
```
$ go get github.com/gophergala2016/addit
```
#### 2. Make your app compatible.
Listen on `PORT` environment variable.
```go
http.ListenAndServe(":" + os.Getenv("PORT"), nil)
```
#### 3. Start addit
```shell
$ cd path/to/go/project/
$ addit
addit v0.1

fetching dependencies...
building...
starting...
Application started on port 58469

input 'help' to list commands or press tab to autocomplete.

> status
Application is running.
> |
```
### Why addit ?
* Coding in Go is already fun, running it should not be boring either.
* No GOPATH worries, get to your project root and leave the rest to addit.
* Should I use `go build`, `install` or `get`? It's addit's worry.
* Interractive shell to manage your app.
* Never stop your app and restart just to see changes. File changes are watched and app is rebuilt automatically.
* Option to run in isolate environment using docker container.

