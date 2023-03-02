# countrycodes
Country Codes module for V.

# Instalation
v install kutlayozger.country

# Sample
```
import kutlayozger.country

fn main() {
    a := country.filter("region", "Indian Ocean")
    println(a)
    b := country.get_category("region")
    println("*** Regions")
    println(b)
    c := country.get_category("currencyCode")
    println("*** All Currency Codes")
    println(c)
}
```