TeoManagerProjects - Sistema de Gerenciamento de Projetos e Equipes

INSTRUCOES PARA EXECUCAO

1. Abra o MySQL Workbench.

2. Importe o banco de dados executando o arquivo:
   banco_de_dados/sistema_projetos.sql

   Esse script cria o banco sistema_projetos, cria as tabelas e insere os usuarios de teste.

3. Abra o NetBeans.

4. No NetBeans, clique em File > Open Project.

5. Selecione a pasta:
   SistemaProjetos

6. Confira a senha do MySQL no arquivo:
   SistemaProjetos/src/main/java/dao/ConexaoBanco.java

   A senha configurada no projeto esta como:
   Vinniteo123.

   Se a senha do MySQL do computador for diferente, altere a constante SENHA nesse arquivo.

7. Execute a classe principal:
   com.mycompany.sistemaprojetos.SistemaProjetos

USUARIOS DE TESTE

Administrador:
Login: admin
Senha: 123456

Gerente:
Login: gerente
Senha: 123456

Colaborador:
Login: colab
Senha: 123456

DICA DE USO

Para melhor visualizacao das telas, use o sistema em tela cheia ou com a janela maximizada. Assim os campos, tabelas, dashboard e relatorios aparecem com melhor alinhamento e leitura.

OBSERVACAO

O projeto foi desenvolvido em Java, com interface grafica em Java Swing, banco de dados MySQL e conexao via JDBC.
