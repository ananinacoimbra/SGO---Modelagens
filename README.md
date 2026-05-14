# 🏅 Sistema de Gestão das Olimpíadas (SGO)

## 📚 Projeto de Software

Projeto desenvolvido para a disciplina de Projeto de Software do curso de Engenharia de Software.

---

# 👥 Integrantes

* Nome do Aluno 1
* Nome do Aluno 2

---

# 📖 Descrição do Projeto

O Sistema de Gestão das Olimpíadas (SGO) foi desenvolvido com o objetivo de auxiliar no gerenciamento de competições olímpicas, permitindo o controle de atletas, países, modalidades, locais de competição e resultados.

O sistema busca organizar informações importantes relacionadas às Olimpíadas, facilitando o gerenciamento das competições e a geração de relatórios de medalhas.

---

# 🎯 Objetivos do Sistema

O sistema deve permitir:

* Cadastro de competições;
* Cadastro de atletas;
* Inscrição de atletas em competições;
* Controle de locais de competição;
* Registro de resultados;
* Geração de relatórios de medalhas;
* Controle de horários para evitar conflitos de competições.

Porque organizar Olimpíadas manualmente claramente parecia uma ótima ideia até alguém perceber que existem milhares de atletas, centenas de provas e humanos erram até organizando fila de padaria.

---

# 📌 Regras de Negócio

## RN01 - Cadastro de Competições

O sistema deve permitir o cadastro de competições contendo:

* Modalidade;
* Data;
* Horário;
* Local;
* Lista de atletas inscritos.

---

## RN02 - Inscrição de Atletas

* Um atleta pode participar de várias competições;
* O atleta deve representar apenas um país por modalidade;
* As inscrições devem possuir status e número identificador.

---

## RN03 - Alocação de Locais

* Um local não pode possuir duas competições simultaneamente;
* O sistema deve verificar conflitos de horário.

---

## RN04 - Controle de Resultados

Após a realização das competições:

* Os resultados devem ser registrados;
* Devem ser definidos ouro, prata e bronze;
* O sistema deve armazenar pontuações e classificações.

---

## RN05 - Relatórios

O sistema deve gerar:

* Relatório de medalhas;
* Ranking de países;
* Relatório de competições.

---

# 🧾 Histórias de Usuário

## US01 - Cadastro de Competição

Como administrador,
quero cadastrar competições,
para organizar as modalidades olímpicas.

---

## US02 - Cadastro de Atletas

Como administrador,
quero cadastrar atletas,
para permitir sua participação nas competições.

---

## US03 - Inscrição de Atletas

Como administrador,
quero inscrever atletas em competições,
para registrar sua participação.

---

## US04 - Alocação de Locais

Como administrador,
quero alocar locais para as competições,
para evitar conflitos de horário.

---

## US05 - Registro de Resultados

Como administrador,
quero registrar os resultados das competições,
para definir os medalhistas.

---

## US06 - Relatório de Medalhas

Como administrador,
quero gerar relatórios de medalhas,
para acompanhar o desempenho dos países.

---

# 🏗️ Tecnologias Utilizadas

* PlantUML
* Graphviz
* UML
* GitHub

A humanidade decidiu criar linguagens específicas só para desenhar caixas conectadas por linhas. E sinceramente? Funcionou melhor do que deveria.

---

# 📂 Estrutura do Repositório

```bash
📦 sistema-gestao-olimpiadas
 ┃
 ┣ 📂 diagramas
 ┃ ┣ 🖼️ diagrama-de-caso-de-uso.png
 ┃ ┣ 🖼️ diagrama-de-classes.png
 ┃ ┣ 🖼️ diagrama-de-pacotes.png
 ┃ ┣ 🖼️ diagrama-de-componentes.png
 ┃ ┗ 🖼️ diagrama-de-implantacao.png
 ┃
 ┗ 📜 README.md
```

---

# 📌 Diagramas UML

## 📍 Diagrama de Caso de Uso

<img width="800px" src="./imagens/diagrama-de-caso-de-uso.png"/>

---

## 📍 Diagrama de Classes

<img width="800px" src="./imagens/diagrama-de-classes.png"/>

---

## 📍 Diagrama de Pacotes

<img width="800px" src="./imagens/diagrama-de-pacotes.png"/>

---

## 📍 Diagrama de Componentes

<img width="800px" src="./imagens/diagrama-de-componentes.png"/>

---

## 📍 Diagrama de Implantação

<img width="800px" src="./imagens/diagrama-de-implantacao.png"/>

---

# 🗃️ Modelagem do Sistema

O sistema foi modelado utilizando UML com foco em:

* Separação de responsabilidades;
* Modularização;
* Organização arquitetural;
* Clareza visual;
* Representação das regras de negócio.

A arquitetura foi dividida em:

* Interface;
* Controllers;
* Services;
* Repositories;
* Banco de Dados.

---

# 🚀 Execução dos Diagramas

Os diagramas podem ser executados utilizando:

## PlantUML

[https://plantuml.com/](https://plantuml.com/)

## Graphviz Online

[https://dreampuf.github.io/GraphvizOnline/](https://dreampuf.github.io/GraphvizOnline/)

---

# 📖 Disciplina

* Disciplina: Projeto de Software
* Curso: Engenharia de Software
* Professor: João Paulo Carneiro Aramuni

---

# ✅ Considerações Finais

O projeto permitiu aplicar conceitos importantes de:

* UML;
* Engenharia de Software;
* Modelagem de Sistemas;
* Arquitetura de Software;
* Organização de requisitos.

Também serviu como lembrete de que modelar sistemas grandes exige muito mais do que simplesmente desenhar caixas aleatórias até parecer tecnológico.
