### Single Inheritance in Go.
```go
type Animal struct{}

func (animal Animal) speak(){
	fmt.Println("Animal makes sound")
}

type Dog struct{
	Animal
}

func (dog Dog) bark(){
	fmt.Println("Dog barks.")
}

func main() {
    dog:=Dog{}
	  dog.speak()
	  dog.bark()
}
```
