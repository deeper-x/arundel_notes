```go
1. checkBool := (err != nil)
2. table-driven tests: slice of structs whit values to check 
3. anonymous structs w/ slices:
var a = []struct{
    a int
    b float64
}{
    {1, 1.0},
    {2. 2.0},
    {3. 3.0},
}
```