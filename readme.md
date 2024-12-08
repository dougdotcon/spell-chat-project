# SpellChat

SpellChat é uma interface de chat com inteligência artificial integrada, permitindo que o usuário interaja em português enquanto recebe respostas em inglês, auxiliando no aprendizado do idioma. A aplicação utiliza a API da OpenAI (GPT-3) para geração de respostas, e conta com reconhecimento de voz (Web Speech API) e síntese de fala, tornando a experiência de interação mais dinâmica e inclusiva.

## Funcionalidades
- Envio de mensagens em texto para o assistente virtual.
- Respostas em inglês geradas pela API da OpenAI.
- Reconhecimento de voz integrado, permitindo ditar as mensagens.
- Conversão de texto em áudio para feedback auditivo.
- Interface responsiva e atraente, utilizando Bootstrap e Font Awesome.

## Tecnologias Utilizadas
- HTML, CSS, JavaScript
- Bootstrap para layout responsivo
- Font Awesome para ícones
- API GPT-3 da OpenAI (necessário possuir uma chave de API)
- Web Speech API para reconhecimento de voz e síntese de fala

## Pré-Requisitos
- Navegador compatível com a Web Speech API.
- Chave de API da OpenAI (substituir `SUA_CHAVE_DA_API_AQUI` no código).

## Como Executar
1. Obtenha uma chave de API da OpenAI.
2. Edite o arquivo `index.html` localizando o trecho do código responsável pela chamada da API GPT-3 e insira sua chave de API.
3. Abra o arquivo `index.html` em seu navegador.
4. Utilize o campo de entrada de texto para enviar mensagens.  
   Opcionalmente, clique no ícone de microfone para ativar o reconhecimento de voz.
5. Aguarde as respostas do assistente exibidas no chat.

## Personalização
- Ajuste estilos no arquivo `style.css`.
- Alterações no layout, cores e fontes podem ser feitas diretamente no código.
- Integrações adicionais, como autenticação ou cache de mensagens, podem ser implementadas de acordo com a necessidade.
