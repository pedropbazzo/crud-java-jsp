# <img src="https://img.shields.io/badge/java%20-FF0000.svg?&style=for-the-badge&logo=java&logoColor=white"/> CRUD Java Web JSP 
CRUD com Java utilizando o gerenciador de dependências Apache Maven 

- Java Web
- Maven
- JSP
- SQL
- JDBC
- JUnit
- Materialize

## Como usar:
### Windows, Linux e MacOS
Primeiros passos
### Aquisição da IDE e do Servidor
- Baixe o [Java 8](https://www.java.com/pt_BR/download/).
- Baixe o [Eclipse IDE](https://www.eclipse.org/downloads/).
- Baixe o [Tomcat 8.5](https://tomcat.apache.org/download-80.cgi).
- Baixe o SQL (Você pode baixar o [MySQL Workbench](https://dev.mysql.com/downloads/workbench/), ou qualquer outro serviço SQL).
- Baixe o [repositório]
### Configuração e instalação
- Java
  - Instalação:
    - Instale a aplicação normalmente
  - Configuração:
    - Não ha necessidade
- Eclipse
  - Instalação:
    - Instale a aplicação normalmente
  - Configuração:
    - Com o Eclipse iniciado, va em:
      - "File"
        - "Open Projects from File System"
          - Selecione o diretorio que você baixou o repositorio da aplicação e clique em "finish".
    - Clique no botão direito na pasta do projeto
      - Va em "Servers" (se encontra na parte inferior do programa, caso não tenha encontrado, procure por ele em "Quick Acess")
        - Clique para adicionar um novo servidor
          - Selecione "Tomcat v8.5 Server" e clique em Next
            - Selecione a pasta em que você baixou o "Tomcat 8.5"
            - Selecione o JRE como: jre_1.8.0_xxx e clique em "Finish"
- SQL
  - Instalação:
    - Instale a aplicação normalmente
  - Configuração:
    - Configure a porta do SQL como padrão (3306)
    
### Uso da aplicação
Com o Eclipse rodando e o projeto selecionado, espere que o Maven baixe todas as dependencias do projeto, logo após, verifique se o SQL esta rodando na porta 3306
- Baixe e execute o Script SQL: [crud_java.sql]
- Clique com o botão direito em cima do nome do projeto e clique em:
  - "Run As"
    - "Run on Server"
      - Selecione o "Tomcat v8.5 Server at localhost" e clique em "Finish"
