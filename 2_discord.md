## Documentació del Bot de Discord

![Logotip de Discord](https://cdn.prod.website-files.com/6257adef93867e50d84d30e2/6995885ab18e401b7eb3c6fc_16x9.webp)

Pots registrar la teva aplicació al [Portal de Desenvolupadors de Discord](https://discord.com/developers/applications).

Per fer que el bot respongui, escoltem l'esdeveniment `messageCreate` i utilitzem el mètode `message.reply()`.

```java
client.on('messageCreate', message => {
if (message.content === 'ping') {
message.reply('pong!');
}
});
```
