---
dg-publish: true
date: 2025-08-04
---
Com Debug Mode ativado, ele principalmente registra cada evento e muda alguns dos textos pra deixar descritivo ao desenvolvedor que estiver usando

## Logging
Ele registra a atividade inteira do aplicativo (ou do memelist) dentro de uma pasta `[local do aplicativo]/log` com nome baseado no horário e dia do aplicativo [^1]
		`ump_memelist-[dia]-[mês]-[ano]-[hora]-[minuto]-[segundo]`
Ele salva em arquivo ao ocorrer um destes eventos:
- Memelist finalizar seu trabalho
- Aplicativo encerrando
- iniciando o "payload mode"
- Reiniciando o software
- Ativando debug mode
- Forçando via uso do [[Console]]
[^1]: a string `dateAndHour` é definida baseada no momento que o app é iniciado.
[to do]