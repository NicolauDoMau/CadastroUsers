#SistemaCadastro - App de Cadastro de Usuários
##Descrição do Projeto
O SistemaCadastro é um aplicativo Android simples para gerenciar o cadastro de usuários. O app permite registrar nome, endereço e telefone de cada usuário e navegar entre a tela principal, o formulário de cadastro e a listagem de registros.

##Interface do Aplicativo
Adicione aqui os prints da sua interface.

##Regras de Negócio
Cada registro contém nome, endereço e telefone.
O usuário deve confirmar antes de salvar um novo cadastro.
A listagem exibe os registros na ordem de cadastro.
A navegação permite voltar ao menu principal a qualquer momento.
Se não houver registros cadastrados, a listagem exibe um aviso.
Os dados são mantidos em memória apenas enquanto o app estiver aberto.
##Tecnologias
Linguagem: Java
Interface: XML
Android SDK: compileSdk 36, minSdk 24, targetSdk 36
###Ferramenta: Android Studio
###Bibliotecas: AndroidX AppCompat, Material Components, Activity, ConstraintLayout
##Funcionalidades
Cadastro de novos usuários com nome, telefone e endereço.
Confirmação de cadastro com diálogo de alerta.
Navegação entre tela principal, cadastro e listagem.
Exibição de registros com botões "Anterior" e "Próximo".
Contador de registros exibindo a posição atual.
Retorno ao menu principal a partir da listagem.
##Estrutura do Projeto
MainActivity.java: gerencia a lista de registros e navegação entre telas.
Registro.java: modelo de dados do usuário.
TelaPrincipal.java: menu inicial com botões para cadastro e listagem.
TelaCadastroUsuario.java: formulário de cadastro de usuários.
TelaListagemUsuario.java: exibe registros cadastrados com navegação.
#Uso
Abra o aplicativo.
Toque em "Cadastrar Usuário" para inserir um novo registro.
Preencha nome, telefone e endereço.
Confirme o cadastro.
Use "Listar Usuários Cadastrados" para ver os registros existentes.
##Observações
Este projeto não possui persistência de dados em disco ou banco de dados.
Todos os registros são armazenados apenas enquanto o app estiver em execução.
