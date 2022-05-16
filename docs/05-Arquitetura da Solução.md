## Arquitetura da Solução

Nesta seção os detalhes técnicos da disposição de arquitetura e hospedagem são mostradas com detalhes.

### Diagrama de Componentes

Os componentes são divididos em três principais módulos, como mostra imagem e detalhes abaixo.

![](RackMultipart20220516-1-ul098z_html_4056e4ccb94d4cdd.png)

Figura X - Arquitetura da Solução

A solução implementada conta com os seguintes módulos:

- **Navegador** - interface do usuário. Telas em HTML, CSS e Javascript.
- **Dados** - dados de clientes e pedidos salvos para exibição e manipulação posterior.
- **Hospedagem** - local onde a página será publicada e disponibilizada para acesso público.

### Hospedagem

A aplicação utiliza o Netlify como hospedagem oficial do projeto. O link de acesso é controlado pelo domínio Netlify , URL exemplo:

[https://link\_exemplo.netlify.app](https://link_exemplo.netlify.app/)

A disponibilização pública do sistema é feita via Netlify Remote, através de um repositório remoto git. Exemplo:

[https://git.heroku.com/link\_exemplo.git](https://git.netlify.app/link_exemplo.git)
