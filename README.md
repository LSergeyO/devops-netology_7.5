# devops-netology_7.5

3.1  
package main  

import "fmt"  

func ft(x float64, y float64) float64 {  
	return x / y  
}  

func main() {  
	fmt.Println(ft(42, 0.3048))  
}  

3.2  
package main  

import "fmt"  

func main() {  
	x := []int{48, 96, 86, 68, 57, 82, 63, 70, 37, 34, 83, 27, 19, 97, 9, 17}  
	min := x[0]  
	for _, v := range x {  
		if v < min {  
			min = v  
		}  
	}  
	fmt.Println(min)  
}  

3.3  
package main  

import "fmt"  

func main() {  
	for i := 1; i <= 100; i++ {  
		if i%3 == 0 {  
			fmt.Println(i)  
		}  
	}  
}  
