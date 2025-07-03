# Exercícios de DML

## Enunciado

Uma escola deseja organizar suas informações em um banco de dados relacional. Para isso, foram criadas as seguintes tabelas:

alunos: armazena os dados dos alunos, contendo um identificador único (id) e o nome do aluno (nome).
cursos: armazena os dados dos cursos oferecidos, contendo um identificador único (id) e o nome do curso (nome).
matriculas: registra as matrículas dos alunos nos cursos, contendo um identificador único (id), o identificador do aluno (aluno_id) e o identificador do curso (curso_id). Os campos aluno_id e curso_id são chaves estrangeiras que referenciam, respectivamente, as tabelas alunos e cursos.
Com base nessas tabelas, desenvolva consultas SQL para responder aos exercícios propostos.

## Exercicios

| **#** | **Categoria**            | **Exercício**                                                                                                         | **Descrição**                                                                                                 |
|-------|--------------------------|-----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| 1     | **Docker**               | Criar docker com MySQL 8.0 (docker compose)                                                                           | Configurar um ambiente MySQL 8.0 usando Docker Compose.                                                       |
| 2     | **DML Básico**           | Criar uma tabela                                                                                                      | Criar uma tabela no banco de dados.                                                                           |
| 3     |                          | Inserir dados em uma tabela                                                                                           | Inserir registros em uma tabela existente.                                                                    |
| 4     |                          | Atualizar dados em uma tabela                                                                                         | Atualizar valores de registros em uma tabela.                                                                 |
| 5     |                          | Excluir dados de uma tabela                                                                                           | Remover registros específicos de uma tabela.                                                                  |
| 6     |                          | Selecionar todos os dados de uma tabela                                                                               | Consultar todos os registros de uma tabela.                                                                   |
| 7     |                          | Selecionar dados com condição                                                                                         | Consultar registros de uma tabela com base em uma condição.                                                   |
| 8     |                          | Inserir múltiplos registros                                                                                           | Inserir vários registros de uma vez em uma tabela.                                                            |
| 9     |                          | Atualizar múltiplos campos                                                                                            | Atualizar mais de um campo em registros de uma tabela.                                                        |
| 10    |                          | Excluir todos os registros                                                                                            | Remover todos os registros de uma tabela.                                                                     |
| 11    | **Exercícios de Join**   | INNER JOIN                                                                                                            | Liste o nome dos alunos e o nome dos cursos em que estão matriculados.                                        |
| 12    |                          | LEFT JOIN                                                                                                             | Liste todos os alunos e, se houver, o nome do curso em que estão matriculados. Inclua alunos sem matrícula.   |
| 13    |                          | RIGHT JOIN                                                                                                            | Liste todos os cursos e, se houver, o nome dos alunos matriculados. Inclua cursos sem alunos matriculados.    |
| 14    |                          | JOIN com condição                                                                                                     | Liste os nomes dos alunos matriculados no curso de 'Matemática'.                                              |
| 15    |                          | JOIN com COUNT                                                                                                        | Mostre o nome de cada curso e a quantidade de alunos matriculados em cada um.                                 |
| 16    |                          | JOIN com múltiplas tabelas                                                                                            | Liste o nome do aluno, o nome do curso e o ID da matrícula.                                                   |
| 17    |                          | FULL OUTER JOIN (simulado)                                                                                            | Liste todos os alunos e todos os cursos, mostrando as combinações possíveis, mesmo sem matrícula.             |
| 18    | **Exercícios de CTE**    | Listar alunos com mais de uma matrícula                                                                               | Crie uma CTE que conte quantas matrículas cada aluno possui e liste apenas os alunos com mais de uma matrícula.|
| 19    |                          | Cursos com mais de 2 alunos                                                                                           | Crie uma CTE para contar o número de alunos por curso e liste apenas os cursos com mais de 2 alunos.          |
| 20    |                          | Alunos sem matrícula                                                                                                  | Use uma CTE para listar todos os alunos que não possuem nenhuma matrícula.                                    |
| 21    |                          | Matrículas recentes                                                                                                   | Crie uma CTE que selecione as matrículas feitas nos últimos 30 dias e liste o nome do aluno e do curso.       |
| 22    |                          | Ranking de cursos por quantidade de alunos                                                                            | Crie uma CTE que conte o número de alunos por curso e mostre um ranking dos cursos do maior para o menor.     |
