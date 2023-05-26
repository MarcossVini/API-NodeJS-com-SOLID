# Projeto Node 

GymPass style app

##RFs(Requisitos Funcionais)
-[] Deve ser possivel se cadastrar;
-[] Deve ser possivel se autenticar;
-[] Deve ser possivel aobter o perfil de um usuário logado;
-[] Deve ser possivel o número de check-ins realizados pelo usuário logado;
-[] Deve ser possivel o usuário obter seu histórico de academias próximas;
-[] Deve ser possivel o usuario realizar o check-in em uma academia;
-[] Deve ser possivel validar o check-in de um usuário;
-[] Deve ser possivel cadastrar uma academia;

##RNS (Regras de Negócios)

-[] O usuário não deve poder se cadastrar com um e-mail duplicado;
-[] O usuário não pode fazer check-in no mesmo dia;
-[] O usuario não pode fazer check-in se não estiver perto(100m) da academia;
-[] o check-in só pode ser validado por administradores;
-[] A academia só pode ser cadastrada por administradores;



##RNFs (Requistos não-Funcionais)

-[] A senha do usuário precisa estar criptografada;
-[] Os dados da aplicação precisam estar persisitidos em um banco PostgreSQL;
-[] Todas listas de dados precisam estar paginadas com 20 items por página;
-[] O usuário deve ser identificado por um JWT (JSON Web token);


Configurações
-Instalar o node: 
    npm init -y;
-instalar o typescript e juntamente tsup pra gerar build pra produção: 
    npm i typescript @types/node tsx tsup -D;
- Instalar o fastify:
    npm i fastify;