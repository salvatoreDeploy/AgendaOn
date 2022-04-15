# AgendaOn

## O que é o AgendaOn?
O AgendaOn é uma aplicação web de agendamento de serviços, clientes e prestadores de serviço;

## Tecnologias usadas

### Front-end
Para desenvolver a parte visual desta aplicação web foi usado html5, css3 e javascript

### Back-end
Para desenvolver a parte funcional desta aplicação web foi usado php OO

### Base de dados
Para a base de dados foi usado MySql

### Detalhes da aplicação
- O sistema é composto do painel administrativo para o gerenciamento de informações de serviços pretadoes e prestadores de serviço e da parte do cliente reservar um horário em um serviço especifico
- O sistema funciona de forma assíncrona, fazendo as requisições via Ajax
- No sistema foi usado POO 
- No sistema foi usado MVC para a organização de arquivos

### Inicialização do Serviço:
- Fazer o Update atraves do composer - `composer update`;
- Configura constante que recebem, path de localização de imagens;
- Criar banco de dados, importando arquivo mysql que esta na pasta `Server/db/`;
- Configurar conexão com banco mediante informçoes locais; 
