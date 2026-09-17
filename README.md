# Discadora — Central de Atendimento

Painel web profissional para organizar contatos, fila de atendimento, roteiro de voz, resultados e abertura de WhatsApp.

## O que já está pronto
- Dashboard responsivo e profissional.
- Importação de contatos por CSV.
- Busca por nome, telefone e empresa.
- Fila de atendimento com próximo contato.
- Histórico de resultados.
- Roteiro editável salvo no navegador.
- Atalho de WhatsApp com mensagem preparada.
- Integração de voz preparada para Twilio Programmable Voice.
- Tratamento de pedido de não receber novas ligações.

## Telefonia
O servidor usa estas variáveis de ambiente:

- `TWILIO_ACCOUNT_SID`
- `TWILIO_AUTH_TOKEN`
- `TWILIO_FROM_NUMBER`
- `PUBLIC_BASE_URL`

Instalação:

```bash
npm install
npm start
```

`PUBLIC_BASE_URL` deve ser a URL pública HTTPS do serviço, sem barra final.

## WhatsApp
O botão do painel abre o WhatsApp do contato. Para envio automático de mensagens depois de uma tecla da ligação, use uma integração oficial do WhatsApp Business.

## Segurança e conformidade
Nunca coloque chaves secretas no frontend ou em repositório público. Use somente contatos que você tenha autorização/base legal para contatar e respeite pedidos de não receber novas ligações. Não apresente limite de crédito, aprovação ou condição financeira como confirmado sem que essa informação tenha sido previamente verificada e esteja autorizada.
