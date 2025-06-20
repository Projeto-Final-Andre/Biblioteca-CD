# 📚 Projeto Final: Análise de Dados com Python - Biblioteca

<img src="img/print_banco.png" />

# _🎯 Introdução & objetivo_

Esse projeto é um sistema de gerenciamento de uma biblioteca comunitária de porte médio, que foi implementada visando a aplicação dos conceitos estudados pela equipe durante as aulas de Banco de Dados. O banco de dados Biblioteca permite a visualização e manipulação dos dados que fazem parte de um sistema literário, gerenciando dados de empréstimos, funcionários e leitores.
O projeto foi implementado no sistema de banco de dados relacional PostgreSQL, com sua modelagem realizada na plataforma digital do Mermaid Chart Inc., utilizando sua ferramenta baseada na linguagem JavaScript para a criação de um diagrama mais limpo e rápido.<br>
**_Acessando a documentação (Projeto Final Banco de Dados Relacional - Biblioteca.docx), é possível visualizar todos os detalhes do projeto._**

# **_👥 Público alvo_**

| Perfil de usuário          | Descrição, necessidades e interesses.                                                                                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Chefe                      | Funcionário chefe da biblioteca, deseja que seus funcionários tenham informações organizados, mas sem acesso a funções que podem prejudicar o funcionamento da biblioteca, somente ele pode mudar configurações mais críticas |
| Funcionário                | Funcionário comum da biblioteca, precisa registrar novos usuários, empréstimos, livros e suas respectivas informações relacionadas.                                                                                           |
| Frequentador da biblioteca | Usuário que precisa saber se realizou empréstimos, data de devolução, quer emprestar livros e ver quais estão disponíveis.                                                                                                    |

# _📁 Usando o projeto localmente_

Siga os passos a seguir para usar o projeto localmente.

<h3>Pré-requisitos</h3>

É necessário ter instalado:

- PostgreeSQL

<h3>Clonando</h3>

Se preferir, pode clonar o projeto localmente para acessar os arquivos, se não, pode vizualizá-los pelo próprio GitHub.

Para clonar o projeto, coloque o seguinte código no terminal:

```bash
git clone https://github.com/Projeto-Final-Andre/Biblioteca-BD.git
```

<h3>Como rodar o projeto</h3>

1. Abra o PostgreSQL
2. Já tendo um servidor, abra o Query Tool (Alt + Shift + Q)
3. Cole no espaço query:

```bash
CREATE DATABASE biblioteca;
```

4. Selecione a database biblioteca e abra o Query Tool novamente
5. Abra o arquivo ddl.sql
6. Copie todos os comandos exceto pelo listado acima
7. Abra o arquivo dmt_dtl.sql
8. Copie todos os comandos listados somente até o SAVEPOINT original;
9. Cole no espaço query
10. Para rodar testes de update e delete, copie os demais códigos do arquivo e cole no mesmo espaço, **_se quiser que as mudanças sejam permanentes, retire o ROLLBACK_**
11. Para realizar as consultas, abra o arquivo dql.sql, copie e cole os comandos individualmente para observar o resultado
12. Para executar o controle de permissões, abra o arquivo dcl.sql, copie e cole todos os comandos no arquivo, para testes, clique em biblioteca/postgre@PostgreSQL na parte superior, < new conection >, selecione a database biblioteca e user, salve, digite a senha do usuário escolhido e digite comandos básicos para verificar se está funcionando.

# _🤝 Contribuidores_

Conheça os contribuidores desse projeto:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/DreBartolomeu">
        <img src="https://avatars.githubusercontent.com/u/138133545?v=4" width="100px;" alt="Andressa Bartolomeu"/><br>
        <sub>
          <b>Andressa Bartolomeu</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/NataliaNogueira1">
        <img src="https://avatars.githubusercontent.com/u/198615971?v=4" width="100px;" alt="Natália Nogueira"/><br>
        <sub>
          <b>Natália Nogueira</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/MarcelaMulato">
        <img src="https://avatars.githubusercontent.com/u/198286703?v=4" width="100px;" alt="Marcela Mulato"/><br>
        <sub>
          <b>Marcela Mulato</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Rodrigof981">
        <img src="https://avatars.githubusercontent.com/u/195812121?v=4" width="100px;" alt="Rodrigo Soares"/><br>
        <sub>
          <b>Rodrigo Soares</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
