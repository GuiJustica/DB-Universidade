# 🎓 Gerador de Dados Sintéticos para Sistema Universitário (CockroachDB)

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)](https://www.python.org/)
[![CockroachDB](https://img.shields.io/badge/Database-CockroachDB-5E5E66?style=flat-square&logo=cockroachlabs)](https://www.cockroachlabs.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

### Trabalho de Banco de Dados - Instituto Universitário DIGIGUI

Este projeto consiste em um *script* em **Python** que automatiza a criação do *schema* de um banco de dados relacional para um Sistema de Gerenciamento Acadêmico e o povoamento com **dados sintéticos realistas**. O sistema é modelado para rodar em **PostgreSQL** (com foco no uso do **CockroachDB**).

---

## 👥 Integrantes do Projeto

* **Diego Jardim** - RA: 24.122.094-6
* **Giovanne Montalvão** - RA: 24.122.029-2
* **Guilherme Justiça** - RA: 24.122.045-8

---

## 💡 Estrutura e Modelagem

### Diagrama Relacional

O banco de dados segue o modelo relacional universitário, englobando 11 entidades principais, como **Alunos**, **Professores**, **Cursos**, **Departamentos**, **Disciplinas**, **Matrizes Curriculares** e **Trabalhos de Conclusão de Curso (TCC)**.
![image](https://github.com/GuiJustica/BancoDeDados/assets/55902652/65690e46-ddeb-4460-b8f5-25e977e8eb34)

### Tecnologias Utilizadas

| Categoria | Tecnologia | Uso |
| :---: | :---: | :--- |
| **Linguagem** | **Python 3.x** | Lógica e automação do *script*. |
| **Banco de Dados** | **PostgreSQL/CockroachDB** | Ambiente alvo para a criação do *schema*. |
| **Driver de Conexão** | **Psycopg2** | Conexão e execução de comandos SQL. |
| **Geração de Dados** | **Faker** e **NumPy** | Geração de nomes, IDs e dados aleatórios realistas em português. |

---


## ⚙️ Configuração e Execução

O script **`projetoDB.py`** é responsável pelo CRUD de todas as tabelas do sistema.

### 1. Pré-requisitos

Certifique-se de ter o **Python 3.x** instalado e as bibliotecas necessárias:

```bash
pip install psycopg2-binary faker numpy
```

## Como conectar o banco de dados
  >Criar seu próprio Cluster no CockroachDB
>
  >Clicar em "connect" para ter as informações de acesso
>
  >Baixar o arquivo projetoDB.py
>
  >Abrir o arquivo python na sua IDE de escolha
>
  >Preencher os dados abaixo de acordo com o seu "connect"
>
>![image](https://github.com/GuiJustica/BancoDeDados/assets/55902652/5d0a5d7e-1373-43ba-ab1c-21ccbdfecc40)
>
  >O "port" padrão do CochroachDB é 26257
>
  >Após isso arquivo deverá ser executado com sucesso!




