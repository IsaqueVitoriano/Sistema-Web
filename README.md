# JP Água & Gás - Sistema Web de Pedidos

Projeto de extensão desenvolvido para a disciplina de Desenvolvimento de Software para Web (2026.2) - Universidade Federal do Ceará (UFC) - Campus Quixadá.

## 1. Registro da Demanda e dos Beneficiários

* **Público beneficiado:** O beneficiário direto é o empreendedor autônomo João Paulo, que atua desde 2024 na entrega de água e gás na cidade de Quixadá. Ele trabalha sozinho, atendendo a cidade inteira todos os dias da semana (das 9h às 20h), prestando um serviço essencial de abastecimento básico para a comunidade local.

* **Interação realizada:** O diálogo com a comunidade foi realizado na data de 19/10/2026 por meio de um questionário digital de levantamento de requisitos enviado via WhatsApp. Durante a pesquisa, ele relatou que recebe pedidos pelo WhatsApp, telefone e presencialmente. A ideia de uma aplicação web foi bem recebida: ele afirmou que "ajudaria muito" ter os pedidos chegando de forma organizada e destacou que uma "tabela de controle ficaria top".
  * **Evidências do contato:** https://drive.google.com/drive/folders/1sHrz9P3_7X2cx2phUkYQcbQjDirzX8-p?usp=sharing

* **Problema identificado:** Atualmente, a gestão de pedidos é feita de forma 100% manual em um "caderninho de papel". O principal problema identificado é a perda de informações: o entregador relatou que, com frequência, esquece de anotar no caderno os pedidos que chegam pelo WhatsApp enquanto está na rua e acaba "deixando o cliente na mão".

* **Escopo:** O objetivo desta primeira versão é desenvolver um sistema Web focado em eliminar a dependência do caderno de papel e centralizar os pedidos.
  * **Funcionalidades essenciais:**
    1. Uma interface mobile simples para o cliente realizar o pedido sem precisar de cadastro prévio;
    2. Um painel (ou tabela de controle) responsivo para o entregador visualizar os pedidos pendentes com as informações exigidas por ele: nome, número de telefone, endereço e detalhes do pedido;
    3. Indicação clara do método de pagamento escolhido.
  * **Limitações:** Nesta primeira versão, o sistema não terá rotas automatizadas via GPS ou controle complexo de estoque, focando na resolução do problema de esquecimento de clientes.

## 2. Como executar e testar o protótipo

Para garantir a coerência e a segurança da aplicação simulando um ambiente real, a equipe optou por separar a visão do cliente da visão administrativa do entregador em arquivos distintos. 

Para avaliar os fluxos, por favor, abra os arquivos no seu navegador conforme as instruções abaixo:

1. **Visão do cliente (acesso público:** Abra o arquivo `index.html`. Esta é a tela focada em conversão rápida onde a comunidade de Quixadá faz os pedidos.
2. **Visão do entregador (acesso restrito):** Abra o arquivo `painel.html`. Esta é a tela exclusiva do João Paulo, apresentando as métricas e a tabela de controle.

## 3. Protótipo e telas

Abaixo estão as capturas de tela do protótipo finalizado, demonstrando a responsividade e a adaptação do layout para diferentes dispositivos:

### Visão do cliente
<img width="1366" height="690" alt="Tela de pedidos no PC" src="https://github.com/user-attachments/assets/3c1113f6-6fa7-4f27-a0ec-7c1d611534b9" />
<img width="1366" height="690" alt="Tela de pedidos no PC" src="https://github.com/user-attachments/assets/9b8184d3-891e-48d0-b804-77d95ad14acf" />
<img width="1366" height="690" alt="Tela de pedidos no mobile" src="https://github.com/user-attachments/assets/4aff216c-9dd7-4613-9697-bf05381e1ab5" />
<img width="1366" height="690" alt="Tela de pedidos no mobile" src="https://github.com/user-attachments/assets/880b1526-8269-4ff7-bf19-4c26476c2753" />


### Visão do entregador
<img width="1366" height="736" alt="Painel do JP no PC" src="https://github.com/user-attachments/assets/93fe546c-089a-47f4-bb14-46a3d6863128" />
<img width="1366" height="690" alt="Painel do JP no PC" src="https://github.com/user-attachments/assets/ef6c17b1-ed6a-4161-a704-2744f9875bfc" />
<img width="1366" height="690" alt="Painel do JP no mobile" src="https://github.com/user-attachments/assets/9d20f59d-dfd5-4a16-aeba-b5cf2655cf93" />
<img width="1366" height="690" alt="Painel do JP no mobile" src="https://github.com/user-attachments/assets/9064f48b-7b7c-47cb-aed6-9941fec524e5" />


## 4. Tecnologias e práticas utilizadas (Etapa 01)

* **HTML5 Semântico**
* **CSS3**
```
