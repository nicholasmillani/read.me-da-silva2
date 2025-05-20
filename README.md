1-Explique com suas palavras o papel de cada camada da arquitetura MVC usada neste projeto.
Como o Model, o Controller e a View interagem entre si?

2-Como ocorre o envio e o recebimento de dados no formato JSON neste projeto?
Cite uma rota que responde em JSON e explique seu funcionamento.

3-Qual a importância de usar HTML básico com formulários e tabelas para organizar e manipular dados no navegador?
Por que esse tipo de estrutura ainda é útil em projetos back-end com Node.js?

#respostas:
1- A camada Model é a que interage diretamente com o banco de dados. A camada controllers recebe as requisições e executa as logicas de negocio. A camada view é a que aparece para o usuário. A interação entre elas ocorre primeriamente com o usuário mexendo no view e enviando/pedindo uma informação, o controller então pega essa requisição aplica as lógicas de negócio, ele então interage com o model que efetivamente se comunica com o Banco de dados.

2- Json é um formato de arquivo que armazena e envia infromações de maneira estruturada, esse tipo de arquivo permite a interação entre banco de dados e a API.
O recebimento é cabe ao controller, que transforma a resposta em json. Não sei um exemplo de rota 

3- O html é essencial para o envio de infromações para o banco de dados, essas que são inputados pelo usuário. Ele ainda é útil pois junto com o express o node  consegue ler arquivos ejs.
