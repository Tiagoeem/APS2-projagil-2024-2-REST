# Exercício de Web Services REST com Flask e PostgreSMySqlQL

Neste exercício, você criará um webservice incorporando os princípios REST até o Nível 2 do Modelo de Maturidade de Richardson. A aplicação deve continuar gerenciando livros e usuários, mas agora com uma abordagem mais padronizada e alinhada com as práticas RESTful. Além disso, você deverá realizar o deploy do webservice no Render.

## Requisitos:

1. **Estrutura de Pastas**:
    - Arquivo principal deve se chamar `app.py`;
    - Deve também ter uma pasta com a colection atualizada do POSTMAN. Não esqueça que deve existir uma request para cada rota;
    - Crie uma pasta para guardar o certificado e um arquivo .cred para armazenar as credenciais de acesso de sua base. É fundamental que você adicione esses arquivos no `.gitignore`;

2. **Recursos e Verbos HTTP**:
    - Seus endpoints devem ser organizados em torno de recursos (por exemplo, `/livros`, `/usuarios` e `/emprestimos`).
    - Utilize os verbos HTTP para representar ações CRUD sobre esses recursos: 
        - **GET** para leitura.
        - **POST** para criação.
        - **PUT** para atualização.
        - **DELETE** para exclusão.
    - Garanta que os códigos de status HTTP sejam usados de forma adequada para representar o resultado de cada operação.

3. **Endpoints RESTful**:
    - As rotas e métodos devem seguir o padrão RESTful. Por exemplo:
        - **GET** `/livros`: Lista todos os livros.
        - **POST** `/livros`: Adiciona um novo livro.
        - **GET** `/livros/1`: Obtém detalhes do livro com ID 1.
        - **PUT** `/livros/1`: Atualiza o livro com ID 1.
        - **DELETE** `/livros/1`: Exclui o livro com ID 1.
    - Siga a mesma lógica para o recurso `/usuarios` e `/emprestimos`.

4. **Testando com Postman**:
    - Crie uma collection no Postman para testar todos os endpoints.
    - Após realizar os testes, exporte a collection atualizada:
        1. No Postman, clique com o botão direito na collection que você criou.
        2. Selecione "Export".
        3. Escolha a versão do formato (recomendamos a versão 2.1).
        4. Clique em "Export" e salve o arquivo na pasta `postman` do projeto.
    - **ATENÇÃO**: A exportação da collection atualizada é essencial e vale pontos. Certifique-se de substituir o arquivo existente na pasta `postman`.


## Observações:

- Deverá ser utilizado o Nível 2 do Modelo de Maturidade de Richardson.
- Lembre-se de que, no Nível 2, é importante não apenas usar verbos HTTP, mas também garantir que os códigos de status HTTP sejam usados corretamente.
- Dê atenção especial à organização dos seus endpoints, garantindo que eles estejam alinhados com os princípios RESTful.


## Fonte de Informação

### Ajuda com o Python utilizando a base MySQL

- Tutorial: [https://www.tutorialspoint.com/postgresql/postgresql_python.htm](https://www.w3schools.com/python/python_mysql_getstarted.asp)

- Documentação oficial: [https://www.psycopg.org/docs/](https://dev.mysql.com/doc/connector-python/en/)

### Ajuda com Flask

- Intro: https://www.tutorialspoint.com/flask/flask_application.htm

- Recebendo JSON via requisição: https://stackabuse.com/how-to-get-and-parse-http-post-body-in-flask-json-and-form-data/

- Variáveis na URL (urls dinâmicas): https://www.geeksforgeeks.org/generating-dynamic-urls-in-flask/

- Query Parameters: https://stackabuse.com/get-request-query-parameters-with-flask/

- Documentação oficial: https://flask.palletsprojects.com/en/3.0.x/

### Ajuda com Postman

- Intro: https://learning.postman.com/docs/getting-started/first-steps/sending-the-first-request/

- Importando uma collection: https://learning.postman.com/docs/getting-started/importing-and-exporting/importing-data/


### Ajuda com Render

- Tutorial: https://slender-ceder-1da.notion.site/Deploy-Flask-Render-65892818212a4c22ba79f90ebca88ced
  


### Busque outras fontes

Fique a vontade para procurar vídeos no youtube caso ache necessário, muitas pessoas aprendem melhor com vídeos.

O ChatGPT usado corretamente pode se tornar um grande parceiro de aprendizado, e te ajudar com conceitos que talvez ainda não estejam tão claros para você, pergunte sobre as ferramentas, integrações e papel de cada um dos elementos presentes nesta tarefa, só não peça por código. Não tome o caminho mais fácil, isso irá te prejudicar mais do que você imagina.
