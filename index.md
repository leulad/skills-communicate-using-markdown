# This is H1 header which i already Knew
## This is supposed to H2 , HTML
### Now this is repetitive
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
```
func calculateTotalTax(taxSystems []taxSystem) int {
    totalTax := 0
    for _, t := range taxSystems {
        totalTax += t.calculateTax() //This is where runtime polymorphism happens
    }
    return totalTax
}
```
