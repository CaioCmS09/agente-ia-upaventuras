# agente-ia-upaventuras
Esse é o assistente de agendamento inteligente via WhatsApp que:
# 🤖 agente-ia-upaventuras

Agente inteligente via WhatsApp para agendamento de visitas no salão de festas **UP Aventuras**, construído com **n8n** e **OpenAI**.

---

## 🌟 Funcionalidades

- Detecta a intenção do cliente em agendar uma visita ao salão
- Responde de forma inteligente e orientada para o agendamento
- Conecta com **Google Calendar API** para verificar disponibilidade
- Transcreve áudios enviados pelos clientes (via **Whisper**)
- Interrompe automaticamente as respostas quando um vendedor humano entra na conversa
- Envia **follow-ups automáticos** para lembrar o cliente da visita
- Automatiza envio de informações úteis: localização, datas, horários, confirmações
- Mantém **memória simples e longa** com uso de Redis
- Utiliza prompts otimizados para conduzir o cliente até a visita

---

## ⚙️ Tecnologias e integrações

- [n8n](https://n8n.io) (automação)
- [OpenAI GPT-4](https://platform.openai.com/)
- [Whisper](https://platform.openai.com/docs/guides/speech-to-text)
- [Google Calendar API](https://developers.google.com/calendar)
- [Redis](https://redis.io) (memória de longo prazo)
- WhatsApp (via Chatwoot, Twilio, Z-API ou outros provedores)

---

📌 Fluxo do agente
![Fluxo parte 1](https://github.com/user-attachments/assets/21fa44b3-e114-4626-9ab9-b4d48fb3ee02)
![Fluxo parte 2](https://github.com/user-attachments/assets/93207f16-af1e-4f87-b661-2a969bebc4ce)
![Fluxo parte 3](https://github.com/user-attachments/assets/a4ca7b7d-ecff-488c-bcc8-693dcb865a35)



