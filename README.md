# post_bot

Bot de Telegram

-Crea publicaciones ayudado por las APIS de [Anilist](https://anilist.gitbook.io/anilist-apiv2-docs/), [Visual Novel Data Base](https://vndb.org), y las envía a un canal de Telegram.

## Para correrlo

Configurar las variables de entorno:

ID_CANAL = -100xxx (el canal donde poner los posts)

TOKEN = el token del bot de telegram que te da [BotFather](https://t.me/BotFather)

SUPPORT = id del grupo/canal donde se anuncia quien ha hecho posts anónimos(para moderación)

DATABASE_URL = dirección de la base de datos, heroku lo llena automáticamente con la base asociada al dyno