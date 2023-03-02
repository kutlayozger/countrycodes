# countrycodes
Country Codes module for V.

# Instalation
v install kutlayozger.countrycodes

# Sample
```
import kutlayozger.countrycodes

fn main() {
    a := filter("region", "Indian Ocean")
    println(a)
    b := get_category("region")
    println("*** Regions")
    println(b)
    c := get_category("currencyCode")
    println("*** All Currency Codes")
    println(c)
}
```