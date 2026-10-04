# Projeto R$ 20K - Rastreador de Metas 💰

Um aplicativo web simples e elegante projetado para ajudar você a acompanhar sua jornada financeira rumo ao objetivo de juntar **R$ 20.000,00 em 2 anos**.

## ✨ Funcionalidades

*   **Painel Dinâmico:** Visualize rapidamente sua meta total, o valor já poupado e quanto falta para atingir o objetivo.
*   **Cálculo Inteligente:** O aplicativo calcula automaticamente a sua meta mensal de economia com base no tempo restante (24 meses a partir da data de início) e no valor que ainda falta.
*   **Barra de Progresso Visual:** Acompanhe seu avanço com uma barra de progresso interativa e animada.
*   **Gestão de Transações:** Adicione depósitos (entradas) e retiradas (saídas) com descrições personalizadas.
*   **Armazenamento Local (Local Storage):** Seus dados são salvos com segurança diretamente no seu navegador. Você pode fechar a página e voltar mais tarde sem perder seu histórico.
*   **Modo Escuro (Dark Mode):** Suporte nativo a tema claro e escuro, sincronizado com o sistema ou controlado manualmente por um botão de alternância.
*   **Design Responsivo:** Interface "Mobile-First" otimizada para funcionar perfeitamente tanto em smartphones quanto em telas maiores.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído de forma totalmente estática e independente de servidores ("serverless") utilizando:

*   **HTML5** para a estrutura semântica.
*   **Tailwind CSS (via CDN)** para estilização rápida, moderna e responsiva.
*   **JavaScript (Vanilla)** para a lógica de negócio, manipulação do DOM e persistência de dados.

## 🚀 Como Executar o Projeto

Como é um aplicativo web focado no lado do cliente (client-side), não é necessário instalar dependências pesadas, como Node.js ou configurar bancos de dados.

1.  Baixe ou copie o arquivo `index.html`.
2.  Dê um duplo clique no arquivo `index.html` para abri-lo no seu navegador web preferido (Chrome, Firefox, Safari, Edge, etc.).
3.  Pronto! O aplicativo criará automaticamente a sua data de início e você já pode começar a registrar seus depósitos.

## 💡 Como Usar

1.  **Primeiro Acesso:** Ao abrir o site pela primeira vez, o projeto inicia automaticamente o prazo de 2 anos a partir da data atual.
2.  **Adicionando Valores:** Use o formulário "Nova Transação" na parte inferior/esquerda. Selecione "Depósito", digite o valor que você guardou e clique em adicionar.
3.  **Removendo Valores:** Se precisar tirar dinheiro da reserva, selecione "Retirada", informe o valor e registre.
4.  **Excluindo Registros:** Cometeu um erro? Basta clicar no ícone de lixeira ao lado da transação no "Histórico de Transações".
5.  **Reiniciando o Projeto:** Se desejar começar tudo do zero, clique no botão vermelho "Zerar e reiniciar projeto" no final do formulário. **Aviso: Isso apagará todo o seu histórico.**

## 📝 Notas

*   Este projeto utiliza a API de `localStorage` do navegador. Se você limpar os dados do navegador (cache/cookies/dados de sites), seu histórico de economia será perdido. 
*   Recomenda-se fazer este controle em conjunto com sua conta bancária real onde o dinheiro está rendendo!
