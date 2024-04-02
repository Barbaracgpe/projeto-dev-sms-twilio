#Bonfim dev SMS Twilio
Projeto Alerta de Vendas.

## Diagrama de Classes

```mermaid
classDiagram
    class User {
        - name: String
        - account: Account
        - news: News[]
    }

    class Account {
        - number: String
    }

    class News {
        - icon: String
        - description: String
    }

    User --|> Account : has
    User --|> News : has many
```
