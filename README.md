# Models 🎲

O model faz a ligação com o banco de dados e quando o controller precisa de algum dado ele vai no model buscar

# Controllers 🕹️

O controller faz a ligação entre um endpoint e o model, basicamente, o endpoint vai fazer uma solicitação, o controller vai analisar essa solicitação e realizar a função para que aquela solicitação seja atendida, para isso, o controller vai até o model buscar os dados necessários para que a função seja realizada e depois o controller vai retornar o resultado daquela ação para o endpoint.

# Endpoints 👩‍💻

O endpoint vai pedir que algo aconteça, ele vai fazer uma solicitação de uma tarefa, por exemplo, ai o controller vai executar essa solicitação e depois vai retornar para o endpoint. No caso do projeto, o view vai mostrar as informações para o usuário, quando o usuário quiser adicionar um aluno, por exemplo, ele vai colocar as informações daquele aluno e apertar o botão Adicionar, ao fazer isso temos um endpoint, essa solicitação de adicionar aluno vai ser enviada para o controller, que vai buscar os dados no model, depois vai realizar a função de adicionar o aluno e devolver que o aluno foi adicionado para que o view possa exibir na tela do usuário que aquele usuário foi adicionado.