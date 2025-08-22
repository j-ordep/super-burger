
# Super Burger

Este projeto é uma aplicação web desenvolvida com Vue.js que simula uma página de hamburgueria. O objetivo é proporcionar uma experiência interativa para o usuário, permitindo visualizar banners, cadastrar pedidos de hambúrguer, acompanhar pedidos e navegar por diferentes seções da hamburgueria.

## Funcionalidades

- **Página inicial com banner**: Apresenta um banner visual atrativo para a hamburgueria.
- **Cadastro de pedidos**: Formulário para o usuário montar e enviar seu pedido de hambúrguer.
- **Dashboard de pedidos**: Visualização dos pedidos realizados, permitindo acompanhar o status.
- **Navegação entre páginas**: Utiliza Vue Router para navegação entre Home, Pedidos e outras páginas.
- **Mensagens de feedback**: Exibe mensagens para informar o usuário sobre ações realizadas (ex: pedido enviado).
- **Layout responsivo**: Interface adaptável para diferentes tamanhos de tela.
- **Imagens ilustrativas**: Utilização de imagens para tornar a experiência mais agradável.

## Estrutura do Projeto

- `src/components`: Componentes reutilizáveis como Banner, BurgerForm, Dashboard, Footer, Message e Navbar.
- `src/views`: Páginas principais como Home e Pedidos.
- `src/router`: Configuração das rotas da aplicação.
- `public/img`: Imagens utilizadas na interface.
- `db/db.json`: Simulação de banco de dados para armazenar pedidos.

## Como executar

1. Instale as dependências:
	```bash
	npm install
	```
2. Inicie o servidor de desenvolvimento:
	```bash
	npm run serve
	```
3. Acesse a aplicação em `http://localhost:8080`

## Tecnologias utilizadas

- Vue.js
- JavaScript
- HTML/CSS

## Sobre

Este projeto foi criado para fins de aprendizado, focando em conceitos de SPA, componentes reutilizáveis, gerenciamento de rotas e simulação de backend com arquivo JSON.

Sinta-se à vontade para contribuir ou adaptar para sua própria hamburgueria! 🍔
