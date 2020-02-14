## Creating Servers
1. Create project 
``` 
$ ~ cd go/src
$ src mkdir directory_name
$ cd directory_name
```

2. go mod init github.com/username/repo
3. work on code --> paste imports
```
$ go get -u github.com/labstack/echo/...
Copy paste 'github.com/labstack/echo/...' into imports (... is the version number ex. v4)
```
4. build or run your code:
--> stores dep version in go.mod
--> stores dep checksum in go.sum