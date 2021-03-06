<table align="center" style="border: 0 !important" border="0"><tr><td align="center" border="0" width="9999">
<img src="https://camo.githubusercontent.com/1f8dec51cb01842d7bb7a7cd50ade17c75c5e3bd/68747470733a2f2f6173736574732e7a6569742e636f2f696d6167652f75706c6f61642f76313533383336313039312f7265706f7369746f726965732f6e6578742d6a732f6e6578742d6a732e706e67" align="center" width="500" alt="Project icon">

### NextJS: SERVER-SIDE RENDERING :computer:
<p>
  <img src="https://img.shields.io/badge/made%20by-Jessica%20Castro-blue?style=plastic">
  <img src="https://img.shields.io/github/license/jessicacastro/nextjs-serverside?color=blue&style=plastic"> 
  <img src="https://img.shields.io/github/stars/jessicacastro/nextjs-serverside?color=blue&style=plastic"> 
  <img src="https://img.shields.io/github/forks/jessicacastro/nextjs-serverside?color=blue&style=plastic"> 
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/jessicacastro/nextjs-serverside?style=plastic">
</p>
</td></tr></table>

## O QUE É O SERVER SIDE RENDERING? POR QUE É UTILIZADO?

Quando robôs indexam os conteúdos do site através de chamadas HTTP, eles acessam o mesmo sem o javascript. O NextJS repassa a responsabilidade para fazer as chamadas iniciais consideradas importantes (como por exemplo para um SEO) para o servidor (NodeJS). Para não perdermos em SEO modificamos essas chamadas direto no servidor passando essas informações para o google, por exemplo, sem que ele perceba.

## CONFIGURANDO A APLICAÇÃO 

1. Antes de tudo, rode o comando: ``yarn init -y`` 
2. Com o package.json criado, rode o comando ``yarn add next react react-dom``

Com essas três dependências já estamos prontos para iniciar nossa aplicação com o NextJS.

3. Crie uma pasta pages com ``mkdir pages``
4. Dentro de pages, crie o arquivo index.js: ``touch index.js``
5. Dentro do "package.json" insira o seguinte:
```
 "scripts": {
    "dev": "next",
    "start": "next start",
    "build": "next build",
  }
```
O script "dev" utilizamos em ambiente de desenvolvimento, e cada vez que editarmos um código, ele gerará a build novamente e nos mostratá via live reload a 
modificaçao na tela.

O script "build" gerará a build com o código totalmente em javascript para enviarmos para o servidor.

Após o build gerado e enviado para o servidor utilizamos o "start" para rodar a build corretamente no servidor.

## RODANDO A APLICAÇÃO

Se você não configurou do zero e clonou este repositório, primeiro dê um ``yarn`` na raiz do repositório, após isso poderá rodar o comando abaixo.

Para rodar a aplicação após a configuração do zero e após o comando yarn: ``yarn dev``. 

<hr>


## :pencil:  Licença MIT
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/jessicacastro/nextjs-serverside/blob/master/LICENSE.md) para mais detalhes.

<hr>

Feito com ♥ by <a href="https://github.com/jessicacastro">Jessica Castro</a>

  
