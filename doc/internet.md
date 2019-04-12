# `Faker.internet`

[Dictionary file](../src/main/resources/locales/en/internet.yml)

Available Functions:  
```kotlin
Faker.internet.freeEmail() // gmail.com
Faker.internet.domainSuffix() // com

// Random user agent by browser type
Faker.internet.userAgent("firefox") // Mozilla/5.0 (Windows NT x.y; Win64; x64; rv:10.0) Gecko/20100101 Firefox/10.0
// or by a random browser type
Faker.internet.userAgent("") // Opera/9.80 (X11; Linux i686; Ubuntu/14.10) Presto/2.12.388 Version/12.16
```