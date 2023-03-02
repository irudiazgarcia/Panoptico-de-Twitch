# Panóptico de Twitch v0.1.0
Script de chat-scrapping o minería de texto basada en API para la plataforma de streaming Twitch.tv, ejecutable a través de la máquina virtual de Google Colab a través de: https://drive.google.com/file/d/1XiJ9mDe6EcDp5lYHilbDIABkYlHJPD-A/view?usp=sharing

## Descripción

El Panóptico de Twitch es una aplicación de Python alojada en la estructura de Jupyter Notebooks que persigue explotar todo el potencial analítico que presenta la API de Twitch (https://dev.twitch.tv/docs/api/) realizando la tabulación ordenada de todos los datos relevantes del scrapping del chat:

|Nombre de la variable  | Descripción |
| ------------- | ------------- |
| badge_info  | Información sobre todas las placas que presenta el usuario  |
| badges  | Tipo de placa del suscriptor por rango  |
| first_ms  | Si corresponde al primer mensaje del *viewer* en el chat  |
| mod  | Si el usuario es moderador del canal  |
| subscriber  | Si el usuario es suscriptor del canal  |
| username  | Nombre de usuario del *viewer*  |
| text  | Contenido del mensaje  |
| months_as_sub  | Nº de meses de suscripción del *viewer* al canal  |
| medal  | Nº de medallas  |
| bits  | Nº de bits donados  en el canal  |
| sub_gifter  | Si ha regalado una suscripción a otro usuario del canal  |
| mentions  | Si el viewer menciona o no a otro usuario en el chat  |
| predictions  | Cuando se llevan a cabo predicciones del canal  |
| amazon_primer  | Si el usuario se encuentra suscrito a Twitch Prime  |
| vip  | Si el usuario ha sido reconocido por el streamer como vip  |
| date  | Fecha del mensaje (GMT+1)  |
| time  | Hora del mensaje (GMT+1)  |
