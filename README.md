# Projeto de Aplicação de Desaparecidos - Polícia Judiciária Civil de Mato Grosso

Este é um projeto prático para o perfil de **Desenvolvedor Front-end**. O objetivo é implementar uma aplicação Single Page Application (SPA) para consultar e interagir com os dados de pessoas desaparecidas fornecidos pela **Polícia Judiciária Civil de Mato Grosso**.


## Descrição do Projeto

A aplicação tem como objetivo possibilitar a consulta de dados de desaparecidos, bem como o envio de informações sobre esses casos. A aplicação foi construída utilizando **React** e algumas bibliotecas e frameworks como **TailwindCSS** para o design e **Axios** para comunicação com a API. A aplicação também inclui funcionalidades de Lazy Loading e Paginação.

### Funcionalidades

1. **Tela Inicial**: Exibe uma lista de desaparecidos ou localizados, com imagens e informações básicas. Inclui paginação para mostrar até 10 desaparecidos por vez.
2. **Tela de Detalhamento**: Exibe detalhes de um desaparecido selecionado, incluindo informações adicionais e a possibilidade de destacar sua situação (desaparecido ou localizado).
3. **Tela de Inclusão de Informações**: Permite que o cidadão envie informações sobre um desaparecido, incluindo máscaras de formatação para os dados e upload de fotografias.

## Tecnologias Utilizadas

- **React** (para o front-end)
- **Axios** (para requisições HTTP)
- **React Router** (para gerenciar as rotas e Lazy Loading)
- **TailwindCSS** (para estilização responsiva)
- **Formik** (para gerenciar formulários)
- **Docker** (para containerização da aplicação)

## Instalação e Execução

Para rodar o projeto localmente, siga as etapas abaixo:


## 1. Clonar o repositório:
Você já fez isso, mas só para garantir, o comando seria:

- git clone https://github.com/LalaGinger/Desaparecidos-PJC.git
- cd projeto-desaparecidos

## 2. Instalar as dependências:
Após navegar até o diretório do projeto, execute:

 - npm install

### Isso vai baixar e instalar todas as dependências definidas no arquivo package.json.

##  3. Rodar a aplicação:

Agora, para rodar a aplicação localmente, execute:
 - npm run dev

### Isso vai iniciar o servidor de desenvolvimento, e você pode acessar a aplicação no navegador através do endereço (normalmente http://localhost:3000 ou http://localhost:5173, dependendo da configuração do Vite). 

### Após entrar no localhost tera uma tela de login 
### User = admin
### Senha = admin

## ⚠️ Observação sobre a API

O site consome dados de uma API externa para exibir informações dinâmicas. Caso os dados não sejam exibidos corretamente na primeira vez que acessar, pode ser necessário **clicar uma vez neste link para ativar a API manualmente** (devido a limitações do serviço gratuito ou cache):

👉 [https://abitus-api.geia.vip/v1/pessoas/aberto?pagina=0&porPagina=1000&direcao=DESC&status=DESAPARECIDO](https://abitus-api.geia.vip/v1/pessoas/aberto?pagina=0&porPagina=1000&direcao=DESC&status=DESAPARECIDO)

Após acessar o link, recarregue o site.



# PROJETO FEITO EM REACT + VITE + TAILWINDCSS
