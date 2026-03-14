```golang
package main

import "fmt"

type AboutMe struct {
	Name        string
	Designation string
	Base        string
}

type Stack struct {
	backend  []string
	frontend []string
	misc     []string
}

func main() {
	me := AboutMe{
		Name:        "Felix",
		Designation: "Cybersecurity",
		Base:        "Ingolstadt, Germany",
	}

	stack := Stack{
		backend:  []string{"Rust", "Go", "Python", "c", "c++"},
		frontend: []string{"React", "Angular", "Typescript", "Tailwind"},
		misc:     []string{"Docker", "Nginx", "PostgreSQL"},
	}

	fmt.Println("About Me:")
	fmt.Printf("%+v\n", me)

	fmt.Println("My Stack:")
	fmt.Printf("%+v\n", stack)
}
```
