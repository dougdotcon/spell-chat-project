
# ✨ SpellChat

**SpellChat** é uma plataforma interativa desenvolvida para aprimorar o aprendizado de idiomas, combinando uma interface amigável, cores suaves e integração com a API da OpenAI (GPT-3). Tenha conversas em português, receba respostas em inglês e melhore sua fluência com recursos de voz, dicas de estudo e um design moderno.

## Recursos Principais

- **Chat Interativo:** Envie mensagens em português e receba respostas em inglês, ampliando seu vocabulário.
- **Reconhecimento de Voz (Speech-to-Text):** Use o microfone para enviar mensagens faladas.
- **Conversão de Texto em Voz (Text-to-Speech):** Ouça as respostas do assistente, aperfeiçoando sua pronúncia.
- **Painel Lateral de Auxílio:** Consulte dicas de estudo, frases comuns e personalize sua experiência (ex.: troca de tema).
- **Layout Responsivo:** Compatível com diferentes dispositivos, garantindo praticidade e mobilidade.
  
## Demonstração Visual

```
 ____________________________
|                            |
|  SpellChat                 |
|----------------------------|
|  Você: "Olá, como vai?"    |
|  Assistente: "Hello, how   |
|             are you doing?"|
|----------------------------|
|  [Microfone]   [Enviar]    |
 ----------------------------
```

## Pré-Requisitos

- Navegador moderno com suporte à [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API).
- Chave de API da OpenAI para o GPT-3.  
  Substitua `SUA_CHAVE_DA_API_AQUI` pelo seu token.

## Como Iniciar

1. Obtenha uma chave de API da OpenAI.
2. No arquivo `index.html`, localize a função `fetchGPT3Response` e insira sua chave na variável `apiKey`.
3. Abra `index.html` no navegador.
4. Digite sua mensagem ou clique no ícone do microfone para falar.
5. Clique em enviar e aguarde a resposta do assistente.

## Personalização

- **Temas & Cores:** Ajuste o CSS para criar novos temas (claro/escuro, diferentes paletas de cores).
- **Armazenamento de Histórico:** Integre o `localStorage` ou um backend simples para manter as conversas.
- **Autenticação & Perfis:** Adicione login para personalizar o aprendizado de cada usuário (nível, preferências, histórico).
- **Recursos Extras:** Crie quizzes, flashcards ou estatísticas de uso para reforçar o aprendizado.

## Tecnologias

- **Front-End:** HTML, CSS, JavaScript, Bootstrap, Font Awesome.
- **APIs:** GPT-3 (OpenAI) e Web Speech API.
- **UI/UX:** Paleta de cores pastéis, tipografia moderna (Open Sans, Poppins) e ícones intuitivos.

---
