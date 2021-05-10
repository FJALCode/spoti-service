# Spoti Service
Web Service a fin de generar un token en [Spotify for Developers](https://developer.spotify.com/).

## Herramientas

Para este proyecto se utilizarón las siguientes herramientas

* [Node](https://nodejs.org/es/)
* [Express](https://expressjs.com/es/)
* [Heroku](https://www.heroku.com/)

## Development environment

```bash
git clone https://github.com/{user}/{ruta}
cd spoti-service
npm install
npm start
```

| Endpoint                           | Tipo | Description                                                                          |
|------------------------------------|------|--------------------------------------------------------------------------------------|
| /spotify/:client_id/:client_secret | GET  | Genera un token usando el client_id y client_secret de la cuenta personal de Spotify |

## Production environment
 Proyecto subido a Heroku [https://spoti-service.herokuapp.com/](https://spoti-service.herokuapp.com/)
 ```ts
 https://spoti-service.herokuapp.com/spotify/:client_id/:client_secret
 ```
 Response
 ```js
 {
  "access_token": "BQBhXOeEt7E7oiJHFi_MDG4WXiMOJtTyCDh5wUhb0hz7t6XXXKDczMjZLsskX-mtHp7xuxJiwqQNjxB5S2h",
  "token_type": "Bearer",
  "expires_in": 3600
}
 ```

## Autor


[<img src="https://avatars2.githubusercontent.com/u/48934580?s=460&v=4" width="100px;"/><br /><sub><b>Fernando Antúnez</b></sub>](https://github.com/FJALCode)<br />[💻](https://github.com/FJALCode "Code") [📢](#talk-Meabed "Talks")

## Expresiones de Gratitud
Proyecto basado en cursos de [Fernando Herrera](https://github.com/Klerith).