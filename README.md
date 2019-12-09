  ####                                              NextJS: SERVER-SIDE RENDERING :computer:



#### O QUE É O SERVER SIDE RENDERING? POR QUE É UTILIZADO?

Quando robôs indexam os conteúdos do site através de chamadas HTTP, eles acessam o mesmo sem o javascript. O NextJS repassa a responsabilidade para fazer as chamadas iniciais consideradas importantes (como por exemplo para um SEO) para o servidor (NodeJS). Para não perdermos em SEO modificamos essas chamadas direto no servidor passando essas informações para o google, por exemplo, sem que ele perceba.

##### INICIANDO E RODANDO A APLICAÇÃO 

1. Antes de tudo, rode o comando: ``yarn init -y`` 
2. Com o package.json criado, rode o comando ``yarn add next react react-dom``

Com essas três dependências já estamos prontos para iniciar nossa aplicação com o NextJS.

3. Crie uma pasta pages com ``mkdir pages``
4. Dentro de pages, crie o arquivo index.js: ``touch index.js``


### :pencil:  Licença MIT
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/jessicacastro/nextjs-serverside/blob/master/LICENSE.md) para mais detalhes.
