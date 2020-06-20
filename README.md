# Desafio2NodeJs-Repository
Desafio 2 de NodeJs do Bootcamp GoStack

Desafio no qual pratiquei alguns conceitos básicos de Node.js. Nesse desafio cria rota que
cria um repositório fictício do github que o usuário informa url, title e techs em array e quantidade de like 0
por padrão, cria rota que altera todos os dados menos os likes, cra rota de listagem e exclusão de repositórios e
cria rota de criar likes que incrementa a cada requisição dessa mesma rota.
Nesse desafio tem validações que impedem o usuário não alterar, excluir e dar likes em repositórios não existentes.
Contém também testes de cada rota para verificar se cada funcionalidade funciona de maneira correta, o framework
Jest é responsável pelos testes.

# Para fazer funcionar a aplicação:

Baixar as dependências do projeto, entrando em seu diretório:
### yarn

# Para executar o projeto:

No diretório do projetco, no terminal executar:
###yarn dev

# Para executar os testes automatizados das rotas:

No diretório do projeto, no terminal executar:
###yarn test
