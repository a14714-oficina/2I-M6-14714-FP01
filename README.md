# 📊 Inventário de Computadores – Aplicação Web (PHP + SQL)

## 👤 Identificação

Este projeto foi desenvolvido no âmbito da disciplina de **REDES – M6 – Programação de Sistemas de Informação** do curso **GPSI – 2.º Ano**.

| Campo      | Detalhe            |
|-----------|--------------------|
| Aluno     | [Nome do Aluno]    |
| Turma     | 2ºI                |
| Disciplina| REDES – M6         |
| Curso     | GPSI – 2.º Ano     |

---

## 🎯 Objetivo do Projeto

O objetivo principal deste projeto é o desenvolvimento de uma **aplicação web para a gestão e consulta de um inventário de computadores** de uma sala informática.

A aplicação utiliza **PHP** para a lógica de backend e **SQL (MySQL)** para a base de dados relacional.

Permite:
- Consultar informações técnicas detalhadas dos computadores  
- Gerir o software instalado em cada equipamento  
- Facilitar a organização, manutenção e controlo dos recursos informáticos  

---

## 🧱 Estrutura Geral do Projeto

O projeto está organizado numa pasta principal chamada **`m6-inventario`**, contendo os seguintes ficheiros:

| Ficheiro            | Descrição |
|--------------------|-----------|
| `config.php`       | Configuração da ligação à base de dados MySQL utilizando PDO (credenciais configuradas localmente). |
| `inventario.sql`   | Script SQL para criação e população inicial da base de dados. |
| `dashboard.php`    | Página inicial com listagem das salas (cards). |
| `index.php`        | Lista os computadores da sala selecionada, com filtros e pesquisa. |
| `pesquisa.php`     | Interface de pesquisa avançada com autocomplete (AJAX/API). |
| `api_pesquisa.php` | Endpoint API em JSON para a pesquisa dinâmica. |
| `detalhe.php`      | Página de detalhes de um computador e gestão do software instalado. |

---

## 🗄️ Base de Dados

A base de dados relacional é composta pelas seguintes tabelas, com chaves primárias e estrangeiras corretamente definidas:

- `salas`
- `computadores`
- `software`
- `computador_software` 

---

## ⚙️ Funcionalidades Desenvolvidas

- Ligação à base de dados com **PHP (PDO)**
- Dashboard com listagem de salas
- Listagem de computadores por sala
- Visualização das características técnicas de cada computador
- Gestão de software por computador:
  - Adicionar
  - Remover
  - Editar versões
- Pesquisa simples por nome de computador ou software
- Pesquisa avançada dinâmica (autocomplete):
  - Nome
  - Sistema Operativo
  - Processador
  - Software
- Geração de PDF com dados dos computadores *(funcionalidade prevista)*
- Interface responsiva para dispositivos móveis
- Melhorias visuais:
  - Cores
  - Layout
  - Ícones Font Awesome

---

## 🤖 Utilização da Inteligência Artificial (IA)

A Inteligência Artificial foi utilizada como **ferramenta de apoio ao desenvolvimento**, respeitando princípios de utilização responsável.

### Onde utilizei IA
- Apoio na escrita e correção de código PHP e JavaScript
- Sugestões para queries SQL complexas (JOIN)
- Organização da estrutura do projeto
- Melhoria do interface gráfico (CSS)
- Resolução de erros e debugging
- Explicação de conceitos técnicos

### Como utilizei a IA
- Exemplos de código e padrões de design
- Identificação e correção de erros
- Sugestões de melhorias visuais e estruturais
- Explicações sobre:
  - PDO
  - AJAX
  - Estruturas relacionais


---

## ✍️ Trabalho Desenvolvido Manualmente

- Criação e organização inicial do projeto
- Estruturação da base de dados relacional
- Implementação das páginas principais:
  - `dashboard.php`
  - `index.php`
  - `detalhe.php`
- Personalização do layout e esquema de cores
- Integração das funcionalidades de navegação, pesquisa e filtros
- Testes e correções de erros
- Documentação final do projeto

---

## 🚧 Dificuldades Encontradas

- Criação correta das relações entre tabelas
- Queries SQL complexas com JOIN
- Implementação da pesquisa dinâmica (AJAX/API)
- Geração correta de ficheiros PDF

---

## 📚 Aprendizagens Realizadas

- Ligação entre PHP e MySQL com **PDO**
- Estruturação de aplicações web
- Bases de dados relacionais e integridade referencial
- Queries SQL avançadas e otimizadas
- Comunicação assíncrona com **AJAX / FETCH**
- Utilização responsável da IA no desenvolvimento

---

## 🔗 Repositório GitHub

🔗 **Link do projeto:**  
[https://a14714-oficina.infinityfree.me/m6-inventario/]
