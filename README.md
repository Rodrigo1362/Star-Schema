# Diagrama Dimensional - Star Schema (Foco: Professores)

Este repositório contém o desenvolvimento de um **Diagrama Dimensional (Star Schema)** com foco na análise de dados relacionados aos professores de uma instituição. O projeto foi modelado a partir de um diagrama relacional previamente fornecido e inclui as tabelas fato e dimensões necessárias para análises no contexto de BI.

## 📂 Estrutura do Repositório
- `script.sql`: Contém o script SQL para criação do esquema dimensional (Star Schema).
- `diagram.png`: Imagem do diagrama gerado no MySQL Workbench.
  
## 🚀 Objetivo
O objetivo principal do projeto é criar um modelo dimensional para análise de dados de professores, incluindo informações sobre:
- Cursos ministrados.
- Departamentos aos quais pertencem.
- Pré-requisitos e disciplinas associadas.
- Dimensão de tempo para granularidade nas análises.

## 🛠️ Tecnologias Utilizadas
- **MySQL Workbench**: Para modelagem e criação do diagrama.
- **SQL**: Para definição das tabelas fato e dimensões.
- **Git**: Para versionamento e compartilhamento do projeto.

## 🗂️ Estrutura do Modelo
### Tabela Fato
**Fato_Professor**: Armazena os dados principais para análise, como IDs de dimensões, cursos ministrados e departamentos.

### Tabelas Dimensão
1. **Dim_Professor**: Informações detalhadas sobre os professores.
2. **Dim_Curso**: Detalhes dos cursos oferecidos.
3. **Dim_Departamento**: Dados sobre os departamentos acadêmicos.
4. **Dim_Disciplina**: Informações das disciplinas.
5. **Dim_Tempo**: Dimensão de tempo para granularidade de datas (oferta de cursos e disciplinas).

