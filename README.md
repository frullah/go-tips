### Check code is running with go test or go run
source : https://stackoverflow.com/a/36666114/4919728
```go
if flag.Lookup("test.v") == nil {
	fmt.Println("normal run")
} else {
	fmt.Println("run under go test")
}
```
