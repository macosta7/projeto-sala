<!-- # Models 🎲 -->

<!-- O model faz a ligação com o banco de dados e quando o controller precisa de algum dado ele vai no model buscar -->

<!-- # Controllers 🕹️ -->

<!-- O controller faz a ligação entre um endpoint e o model, basicamente, o endpoint vai fazer uma solicitação, o controller vai analisar essa solicitação e realizar a função para que aquela solicitação seja atendida, para isso, o controller vai até o model buscar os dados necessários para que a função seja realizada e depois o controller vai retornar o resultado daquela ação para o endpoint. -->

<!-- # Endpoints 👩‍💻 -->

<!-- O endpoint vai pedir que algo aconteça, ele vai fazer uma solicitação de uma tarefa, por exemplo, ai o controller vai executar essa solicitação e depois vai retornar para o endpoint. No caso do projeto, o view vai mostrar as informações para o usuário, quando o usuário quiser adicionar um aluno, por exemplo, ele vai colocar as informações daquele aluno e apertar o botão Adicionar, ao fazer isso temos um endpoint, essa solicitação de adicionar aluno vai ser enviada para o controller, que vai buscar os dados no model, depois vai realizar a função de adicionar o aluno e devolver que o aluno foi adicionado para que o view possa exibir na tela do usuário que aquele usuário foi adicionado. -->

# Como o Model, o Controller e a View interagem entre si? 🧠

O model faz a ligação com o banco de dados. O controller é a ponte entre o view e o model, basicamente o usuário vai querer fazer alguma coisa no site, por exemplo mostrar todos os alunos, o view vai enviar essa informação para o controller que irá procesar as informações e se comunicar com o model para poder executar a ação e depois retornar para o view. O view mostra as informações que o usuário pode ver e faz requisições para o controller.

# Cite uma rota que responde em JSON e explique seu funcionamento. 🎲

Uma rota que responde em JSON é a rota de editar as informações de um aluno, por exemplo. O usuário vai colocar as novas informações daquele aluno, ai o JSON vai pegar essas informações e atualizar elas no banco de dados. O JSON pode ser comparado com POO pois com ele podemos manipular um objeto.

# Qual a importância de usar HTML básico com formulários e tabelas para organizar e manipular dados no navegador? 🧭

O HTML básico com formulários e tabelas facilita a coleta e visualização estruturada de dados diretamente no navegador.
Com isso, se torna mais simples e facilita fazer teste durante o desenvolvimento do site, mesmo em utilizando o Node.js, é útil para utilizar o CRUD de maneira rápida e sem frameworks complexos.
