## **SQL**

A **linguagem de consulta estruturada** ( SQL) permite que os analistas de dados se comuniquem com os bancos de dados. O SQL é uma das ferramentas mais úteis para os analistas, especialmente ao trabalhar com grandes conjuntos de dados em tabelas. Sendo utilizada em:

- Investigação de bancos de dados enormes
- Rastrear strings
- Filtrar dados

E tudo isso de uma maneira muito mais rápida que uma planilha.

### O que é uma consula?

É uma solicitação de dados ou informações de um banco de dados. A sintaxe de cada consulta SQL é a mesma.

- **SELECT** para escolher as colunas que deseja retornar
  - Se utilizar **SELECT***, selecionará todas as colunas da tabela ao invés de uma em especifica.

- **FROM** para escoher as tableas em que estão localizadas as colunas que você quer
- **WHERE** para filtrar informações
  - Cláusula **LIKE**: Procurar um determinado padrão. O sinal de porcentagem **%** é usado como curinga para corresponder a um ou mais caracteres.

Seguir esse método de estrutura sempre facilita a escrita de consutlas SQL e ajuda também a cometer menos erros de sintaxe.

Exemplos:

![Example code](\assets\SQL.png)

### Boas práticas 

- Usar letras maiúsculas e recuo pode ajudar a ler as informações com mais facilidade.
- O ponto e vírgula encerra instruções, faz parte da norma SQL-92 do American National Standards Institute e é uma sintaxe comum para adoção por todos os bancos de dados SQL.
- Comentário podem ser adicionados depois de dois travessões (**--**)
- Atribuir novos nomes de colunas ou tableas usando a cláusula **AS**. **Eles não alteram o nome rea no banco de dados**

## Referências

[SQL Tutorial - W3 Schools](https://www.w3schools.com/sql/default.asp)

[SQL Cheat Sheet](hackmd.io/?nav=overview)