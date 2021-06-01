Funcionamento da Agenda

1 - Abrir a pasta src/teste/resource --> br.com.agendaRiciere.daotest;

2 - Executar "hibernate.cfg.xml" para a criação do banco de dados;

3 - Alterar "create" para "validate", após a criação do banco de dados;

4 - Abrir a pasta src/teste/java --> br.com.agendaRiciere.daotest;

5 - Abrir o "AgendaDaoTest", ele é responsável por testas os métodos de incluir, alterar, deletar, listar e buscar. É possível testa-o para verificar se o banco de dados, está funcionando corretamente;

6 - O @Ignore é utilizado para que o compilador ignore a execução de determinadas linhas de códigos do programa. Ele está sendo utilizado para que ocorra a execução apenas de determinados métodos.

5 - É necessario comentar o @Ignore para que o funcionamento do método escolhido ocorra normalmente (Salvar, Listar, Buscar, Excluir, Editar);

6 - Remover os comentários do @Ignore fará com que tais métodos, sejam ignorados;

8 - Abrir src --> main --> webapp --> pages;

9 - Dentro da pasta "pages", está localizados os arquivos das páginas escritas em xhtml, sendo necessário executa-las no servidor (Run on Server);
