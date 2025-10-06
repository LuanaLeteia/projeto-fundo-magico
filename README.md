# 🎨 Gerador de Background

O Gerador de Background é uma aplicação web integrada ao n8n que permite criar backgrounds personalizados de forma automática com ajuda de inteligência artificial.
O usuário faz uma solicitação descrevendo o tipo de fundo desejado, e o sistema retorna o código HTML e CSS prontos para uso em qualquer projeto.

⚙️ O arquivo workflow-projeto-gerador-background.json contém o fluxo completo para importação no n8n.



## 💻 Tecnologias utilizadas

- HTML
- CSS
- JavaScript
- n8n
- API Gemini



## 🚀 Como funciona

1. O usuário insere uma descrição do background desejado (ex: "um fundo degradê em tons de azul e roxo com animação sutil").
2. Essa solicitação é enviada ao workflow do n8n.
3. O n8n utiliza a IA configurada no fluxo para gerar o código HTML e CSS correspondentes.
4. A resposta é enviada de volta para a página, exibindo os códigos prontos para copiar e usar.



## 🧠 Integração com o n8n

- O projeto utiliza um workflow do n8n para;
- Receber as solicitações do front-end;
- Processar o prompt através de uma IA Gemini;
- Retornar a resposta com os códigos gerados.


## Preview
<img width="1348" height="629" alt="image" src="https://github.com/user-attachments/assets/aa4e4bce-bf2a-4269-bf5f-f1b85d9b9ed4" />


