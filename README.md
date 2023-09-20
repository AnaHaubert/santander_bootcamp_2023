# Santander Bootcamp 2023
Java RESTful API.

## Diagrama de Classes

```mermaid
classDiagram
  class User {
    -String name
    -Account account
    -Feature[] features
    -Card card
    -News[] news
  }

  class Account {
    -String number
    -String agency
    -Number balance
    -Number limit
  }

  class Feature {
    -String icon
    -String description
  }

  class Card {
    -String number
    -Number limit
  }

  class News {
    -String icon
    -String description
  }

  User "1" *-- "1" Account
  User "1" *-- "N" Feature
  User "1" *-- "1" Card
  User "1" *-- "N" News
```

🔗 [Clique aqui para acessar]([https://anahaubert.github.io/SNAKE-GAME/](https://santanderbootcamp2023-prd.up.railway.app/swagger-ui/index.html)https://santanderbootcamp2023-prd.up.railway.app/swagger-ui/index.html)
