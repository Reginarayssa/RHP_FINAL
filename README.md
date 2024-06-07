
# Introdução  
Bem-vindo ao Readme da aplicação para inserção de dados em tabelas do Real Hospital Português! Este guia detalhado irá te auxiliar na instalação, configuração e execução da aplicação, que é composto por um backend Node.js e um frontend React. O banco de dados Oracle é utilizado para armazenar os dados.

# Pré-requisitos
Antes de começar, certifique-se de ter os seguintes softwares instalados em sua máquina:

Node.js (versão 16 ou superior)
npm (instalado globalmente)
Conta Oracle(sqldeveloper) com acesso ao servidor

# Instalação
Clone o repositório do aplicativo:

No terminal do VsCode:
```git clone https://github.com/Reginarayssa/RHP_EntregaFinal.git```


Acesse as pastas do backend(RHP_Servidor) e do frontend(RHP_Cliente):

No terminal do VsCode, execute o comando ```npm install``` na raiz do projeto, em seguida, ```cd RHP_Servidor``` seguido de  ```npm install``` e a mesma coisa na pasta do front.  ```cd RHP_Cliente``` > ```npm install```. para instalar as todas as dependências do projeto.

Na pasta RHP_Servidor, na pasta "config", acesse o arquivo "db.js" e substitua as credenciais  (user, password e connectString) para a do seu banco de dados ORACLE.

# Execução do Aplicativo
Na pasta RHP_Servidor:
Inicie o servidor backend no terminal com o comando  
```npm start```

Na pasta RHP_Cliente:
Inicie o servidor backend no terminal com o comando  
```npm start```





