# Projeto: Somente Membros! 

* 1 Crie um modelo Post e um controlador Posts e um recurso correspondente em seu arquivo Routes que permite os [:new, :create, :index]métodos.

* 2 No topo do seu Posts Controller, use a #before_actionpara restringir o acesso aos métodos #newe #createapenas aos usuários que estão conectados.

* 3 Para o seu Posts Controller, prepare sua #newação.

* 4 Escreva um formulário na app/views/posts/new.html.erbvisualização que criará uma nova postagem.

* 5 Faça com que sua #createação correspondente crie uma postagem onde a chave estrangeira do autor (por exemplo, user_id) seja preenchida automaticamente com base no usuário conectado. Redirecione para a visualização do Índice se for bem-sucedido.

* 6 Preencha a #indexação do PostsController e crie a view correspondente. A visualização deve mostrar uma lista de cada postagem.

* 7 Agora adicione lógica na visualização do Índice para exibir o nome do autor, mas somente se um usuário estiver conectado.

* 8 Faça login e crie algumas postagens secretas.

* 9 Teste – saia e vá para a página de índice. Você deverá ver uma lista das postagens, mas nenhum nome de autor. Faça login e os nomes dos autores deverão aparecer. Seus segredos estão seguros!
