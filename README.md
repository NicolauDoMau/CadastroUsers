# 📱 SistemaCadastro - App de Cadastro de Usuários

## 📖 Descrição do Projeto

O **SistemaCadastro** é um aplicativo Android desenvolvido em Java para gerenciamento simples de usuários cadastrados.

O aplicativo permite:

- ✅ Cadastrar usuários
- ✅ Visualizar registros cadastrados
- ✅ Navegar entre telas
- ✅ Confirmar ações antes do salvamento

Cada usuário possui:

- 👤 Nome
- 📍 Endereço
- 📞 Telefone

---

# 🖼️ Interface do Aplicativo

> Adicione aqui os prints/screenshots do aplicativo.

Exemplo:

```md
![Tela Principal](imagens/tela-principal.png)
![Tela Cadastro](imagens/tela-cadastro.png)
![Tela Listagem](imagens/tela-listagem.png)
```

---

# ⚙️ Regras de Negócio

- Cada registro deve conter:
  - Nome
  - Endereço
  - Telefone

- O usuário deve confirmar antes de salvar um cadastro.

- A listagem exibe os registros na ordem em que foram cadastrados.

- É possível retornar ao menu principal a qualquer momento.

- Caso não existam registros cadastrados, o sistema exibe uma mensagem de aviso.

- Os dados permanecem armazenados apenas enquanto o aplicativo estiver aberto.

---

# 🛠️ Tecnologias Utilizadas

## 💻 Linguagem

- Java

## 🎨 Interface

- XML

## 📱 Android SDK

| Configuração | Versão |
|---|---|
| compileSdk | 36 |
| minSdk | 24 |
| targetSdk | 36 |

---

# 🧰 Ferramentas

- Android Studio

---

# 📚 Bibliotecas Utilizadas

- AndroidX AppCompat
- Material Components
- Android Activity
- ConstraintLayout

---

# ✨ Funcionalidades

- 📌 Cadastro de usuários
- 📌 Navegação entre telas
- 📌 Confirmação de cadastro com AlertDialog
- 📌 Listagem de usuários cadastrados
- 📌 Navegação entre registros com:
  - Botão **Anterior**
  - Botão **Próximo**
- 📌 Contador de registros
- 📌 Retorno ao menu principal

---

# 📂 Estrutura do Projeto

```bash
📦 SistemaCadastro
 ┣ 📂 java
 ┃ ┣ 📜 MainActivity.java
 ┃ ┣ 📜 Registro.java
 ┃ ┣ 📜 TelaPrincipal.java
 ┃ ┣ 📜 TelaCadastroUsuario.java
 ┃ ┗ 📜 TelaListagemUsuario.java
 ┃
 ┣ 📂 res
 ┃ ┣ 📂 layout
 ┃ ┣ 📂 drawable
 ┃ ┗ 📂 values
 ┃
 ┗ 📜 AndroidManifest.xml
```

---

# 📄 Descrição das Classes

| Classe | Função |
|---|---|
| `MainActivity.java` | Gerencia registros e navegação |
| `Registro.java` | Modelo de dados do usuário |
| `TelaPrincipal.java` | Tela inicial do aplicativo |
| `TelaCadastroUsuario.java` | Formulário de cadastro |
| `TelaListagemUsuario.java` | Exibe os registros cadastrados |

---

# 🚀 Como Usar

1. Abra o aplicativo
2. Toque em **Cadastrar Usuário**
3. Preencha:
   - Nome
   - Telefone
   - Endereço
4. Confirme o cadastro
5. Acesse **Listar Usuários Cadastrados**
6. Navegue entre os registros

---

# ⚠️ Observações

> Este projeto não possui persistência em banco de dados ou armazenamento interno.

Todos os registros permanecem disponíveis apenas enquanto o aplicativo estiver em execução.

---

# 👨‍💻 Autor

Projeto desenvolvido para fins acadêmicos e aprendizado em desenvolvimento Android com Java.

```
