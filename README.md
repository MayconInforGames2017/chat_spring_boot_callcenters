# Projeto de CallcentersWeb

Projeto web desenvolvido para atender callcenters consumindo uma API com SpringBoot

Projeto web desenvolvido para uma vaga de estagio na empresa MIDIAVOX.

Bibliotecas tecnicas utilizadas:
- SpringBoot;
- WebSocket;
- ReactorNetty;

```java
	@MessageMapping("/chat.send")
	@SendTo("/topic/public")
	public ChatMessage sendMessage(@Payload ChatMessage chatMessage) {
		return chatMessage;
	}

```

![Dashboard](https://imgur.com/a/tWBkEcv "Dashboard")
