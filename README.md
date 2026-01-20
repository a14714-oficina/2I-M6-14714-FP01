# 📊 Inventário de Computadores – Aplicação Web (PHP + SQL)

## 👤 Identificação
- **Nome do aluno:Carlos Alves**  
- **Turma:2ºI**  
- **Disciplina:** REDES – M6 – Programação de Sistemas de Informação  
- **Curso:** GPSI – 2.º Ano  

---

## 🎯 Objetivo do Projeto
Este projeto consiste no desenvolvimento de uma aplicação web para gestão e consulta de um inventário de computadores de uma sala informática, utilizando PHP para a lógica da aplicação e SQL para a base de dados.

A aplicação permite consultar informações técnicas dos computadores e o software instalado em cada equipamento.

---

## 🧱 Estrutura Geral do Projeto
O projeto está organizado em uma pasta principal contendo os seguintes arquivos:

config.php: Arquivo de configuração para ligação à base de dados MySQL usando PDO.
index.php: Página principal com listagem de computadores, filtros por sala, pesquisa por nome de computador ou software, e botão para gerar PDF.
detalhe.php: Página de detalhes de um computador específico, mostrando características técnicas e permitindo gestão de software (adicionar, remover, editar versões).
inventario.sql: Arquivo SQL para criação e população da base de dados, incluindo tabelas para salas, computadores, software e associações.
fpdf.php: Biblioteca externa (FPDF) para geração de PDFs (baixada de http://www.fpdf.org/).
A base de dados relacional inclui as tabelas: salas, computadores, software e computador_software, com chaves primárias e estrangeiras apropriadas para garantir integridade.

---

## ⚙️ Funcionalidades Desenvolvidas
Lista das funcionalidades que foram efetivamente implementadas no projeto:

- [ ] Ligação à base de dados com PHP (PDO)
- [ ] Listagem de computadores por sala
- [ ] Visualização das características técnicas de cada computador
- [ ] Consulta do software instalado
- [ ] Página de detalhe por computador
- [ ] Pesquisa por nome de computador
- [ ] Pesquisa por software
- [ ] Organização do dashboard
- [ ] Melhorias visuais no interface (cores, layout, ícones)
- [ ] Outras funcionalidades (especificar):

---

## 🤖 Utilização da Inteligência Artificial (IA)
Nesta secção descrevo de forma clara como utilizei Inteligência Artificial no desenvolvimento do projeto.

### 🔹 Onde utilizei IA
(Exemplos – apagar os que não se aplicam e acrescentar outros)

- Apoio na escrita ou correção de código PHP  
- Sugestões para queries SQL  
- Ajuda na estruturação da base de dados  
- Melhoria do interface gráfico (CSS / layout)  
- Implementação da funcionalidade de pesquisa  
- Organização do dashboard  
- Resolução de erros ou problemas técnicos  

### 🔹 Como utilizei a IA
Descrição breve do tipo de apoio recebido, por exemplo:
- A IA sugeriu exemplos de código que foram adaptados;
- Ajudou a compreender erros e respetivas correções;
- Sugeriu melhorias visuais ou estruturais.

---

## ✍️ Trabalho Desenvolvido Manualmente
Descrição das partes do projeto que foram desenvolvidas diretamente pelo aluno, por exemplo:
- Adaptação e personalização do código;
- Implementação final das funcionalidades;
- Decisões de organização do projeto;
- Alterações feitas às sugestões da IA.

---

## 🚧 Dificuldades Encontradas
Descrição das principais dificuldades técnicas ou conceptuais encontradas durante o desenvolvimento do projeto.

---

## 📚 Aprendizagens Realizadas
Reflexão sobre o que foi aprendido com este trabalho, por exemplo:
- Ligação entre PHP e base de dados;
- Organização de um projeto web;
- Utilização consciente da Inteligência Artificial;
- Importância da documentação do código.

---

## 🔗 Repositório GitHub
Link para o repositório do projeto:
