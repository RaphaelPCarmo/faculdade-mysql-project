# 🐘 Atividades MySQL - Projeto de Banco de Dados

Este repositório contém **quatro atividades práticas em SQL**, desenvolvidas como parte do aprendizado em **Banco de Dados** no curso de Ciência da Computação.  
As atividades abordam criação de tabelas, relacionamentos, consultas, atualizações e exclusões, utilizando **MySQL** como SGBD.


## 🛠️ Tecnologias Utilizadas

* ![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)
* ![SQL](https://img.shields.io/badge/SQL-FFCA28?style=for-the-badge&logo=sqlite&logoColor=black)
* ![Workbench](https://img.shields.io/badge/MySQL%20Workbench-4479A1?style=for-the-badge&logo=mysql&logoColor=white)


## 📂 Atividades Incluídas



### 1️⃣ Atividade 1 - Cadastro de Pessoas

Criação da tabela `pessoa` com dados de identificação e endereço.

**Comandos Utilizados:**
- `CREATE TABLE`, `INSERT`, `SELECT`, `DELETE`, `UPDATE`
- Filtros com `WHERE`, `MOD`, e múltiplas condições

**Consultas em destaque:**
- Pessoas com mais de 2 irmãos  
- Endereços de uma pessoa específica  
- Pessoas com número da casa par em Jaguariúna  
- Atualizações e remoções específicas  

📄 Arquivo: `atividade1_pessoa.sql`


### 2️⃣ Atividade 2 - Cadastro de Animais

Criação de uma tabela `animal` com dados como espécie, raça e data de nascimento.

**Comandos Utilizados:**
- Inserção de registros
- Consultas com filtros simples e compostos
- Atualização de atributos específicos (`raca`, `data_nascimento`)
- Exclusão de registros com `DELETE`

**Consultas em destaque:**
- Animais da espécie "Cachorro"
- Alteração de dados de um animal específico
- Consulta por raças e espécies variadas

📄 Arquivo: `atividade2_animal.sql`


### 3️⃣ Atividade 3 - Relacionamento Adulto ↔ Bebê

Criação de duas tabelas (`adulto`, `bebe`) com chave estrangeira representando o vínculo entre pai/mãe e filho(a).

**Conceitos Abordados:**
- Relacionamentos `1:N` com `FOREIGN KEY`
- `INNER JOIN` e `LEFT JOIN`
- Filtragem por estado civil e sexo
- Filtros com `MOD` para identificar pares/ímpares

**Consultas em destaque:**
- Nome dos adultos e seus respectivos bebês
- Pessoas solteiras e do sexo feminino
- Relações entre adultos e bebês com `JOIN`

📄 Arquivo: `atividade3_adulto_bebe.sql`


### 4️⃣ Atividade 4 - Sistema de Agendamento Veterinário

Simula um sistema com três tabelas: `responsavel`, `cachorro` e `agenda`, com relacionamentos e dados reais.

**Comandos e Conceitos:**
- `CREATE DATABASE`, `FOREIGN KEY`, relacionamentos múltiplos
- `COUNT`, `SUM`, `MAX`, `GROUP BY`, `ORDER BY`

**Consultas em destaque:**
- Número de cachorros por responsável
- Total de atendimentos por cachorro
- Soma dos valores pagos em consultas
- Responsável com maior valor de consulta pago

📄 Arquivo: `atividade4_veterinaria.sql`


## 🚀 Como Executar

1. Abra o **MySQL Workbench** ou qualquer terminal de SQL compatível
2. Copie o conteúdo dos arquivos `.sql` da atividade desejada
3. Execute os scripts em sua instância local do MySQL
4. Verifique as tabelas, registros e resultados das consultas

## 🎯 Objetivo do Projeto

🔸 Praticar os fundamentos de banco de dados relacionais com SQL  
🔸 Desenvolver lógica para modelagem de dados  
🔸 Explorar relacionamentos entre tabelas usando `JOIN`  
🔸 Usar comandos de agrupamento, ordenação e filtros complexos


## 👨‍🎓 Autor

<img src="https://github.com/RaphaelPCarmo.png" width="120" style="border-radius: 50%"><br>
<strong>Raphael Perim do Carmo</strong>  
🎓 Estudante de Ciência da Computação  
📍 Brasil  
🔗 GitHub: [@RaphaelPCarmo](https://github.com/RaphaelPCarmo)



## 📄 Licença

Este projeto foi criado com fins educacionais e está disponível para estudo e modificação.  
Sinta-se à vontade para usar como base em seus próprios projetos e portfólio!

