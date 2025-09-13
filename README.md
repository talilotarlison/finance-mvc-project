## Finance MVC Project

### Projeto PHP Puro com SQLite - Padrão MVC

Este é um projeto desenvolvido em **PHP puro** utilizando banco de dados **SQLite** e seguindo a arquitetura **MVC (Model-View-Controller)**. O objetivo é demonstrar a estrutura básica e a organização de um projeto simples, limpo e funcional sem uso de frameworks.

---

## 🧱 Estrutura do Projeto

## 📁 Estrutura do Projeto

Abaixo está a descrição da estrutura de pastas e arquivos do projeto, com base no padrão **MVC** e boas práticas de organização:

| Caminho / Arquivo   | Função                                                                 |
|---------------------|------------------------------------------------------------------------|
| `controllers/`      | ✅ Parte do MVC. Controladores que lidam com as requisições e ações.   |
| `models/`           | ✅ Parte do MVC. Representação de dados e lógica de negócio.           |
| `views/`            | ✅ Parte do MVC. Arquivos de apresentação (HTML, templates).           |
| `services/`         | ⚙️ Complemento útil. Classes auxiliares, lógicas reutilizáveis.        |
| `database/`         | 🗃️ Scripts SQL, arquivos de conexão, ou organização do banco.          |
| `finance.db`        | 🧩 Banco de dados SQLite (pode ser movido para `database/`).            |
| `index.php`         | 🚪 Ponto de entrada da aplicação. Inicializa e encaminha as requisições. |
| `router.php`        | 🧭 Roteador. Interpreta URLs e direciona para o controller adequado.    |
| `README.md`         | 📘 Documentação principal do projeto.                                  |
| `CHANGELOG.md`      | 📝 Histórico de mudanças e versões do projeto.                         |

> ⚠️ Observação: Esta estrutura é compatível com o padrão **MVC** e pode ser expandida conforme o projeto crescer.


## 📌 Explicando os Papéis
| Pasta / Arquivo | Função                                                                      | Parte do MVC?                                          |
| --------------- | --------------------------------------------------------------------------- | ------------------------------------------------------ |
| `controllers/`  | Controladores da aplicação (lógica das requisições)                         | ✅ Sim                                                  |
| `models/`       | Classes que representam dados e regras de negócio                           | ✅ Sim                                                  |
| `views/`        | HTML e output para o usuário final                                          | ✅ Sim                                                  |
| `services/`     | Classes auxiliares (ex: lógica de negócio reutilizável, validação, helpers) | 🔄 Suporte ao MVC                                      |
| `database/`     | Scripts de criação de tabela, seeds ou abstração de conexão                 | ❌ Não diretamente, mas útil                            |
| `finance.db`    | Arquivo de banco SQLite                                                     | ❌ Não parte do padrão, mas essencial para persistência |
| `index.php`     | Entrada principal (chama o roteador, carrega a aplicação)                   | ✅ Sim (geralmente chama o controller certo)            |
| `router.php`    | Arquivo de roteamento (transforma URLs em chamadas de controller/método)    | ✅ Sim, é a cola entre `index.php` e os controllers     |
| `README.md`     | Explicação do projeto                                                       | ❌ Não faz parte da arquitetura                         |
| `CHANGELOG.md`  | Histórico de mudanças                                                       | ❌ Não faz parte da arquitetura                         |


---

## 🔧 Tecnologias Utilizadas

- **PHP 7+**
- **SQLite** (banco de dados leve e embutido)
- **HTML/CSS** (nas views)
- Arquitetura **MVC** (Model-View-Controller)

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

- PHP instalado (7.4 ou superior)
- Servidor embutido do PHP ou Apache/Nginx

### Passos

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git


---

## 🔧 Tecnologias Utilizadas

- **PHP 7+**
- **SQLite** (banco de dados leve e embutido)
- **HTML/CSS** (nas views)
- Arquitetura **MVC** (Model-View-Controller)

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

- PHP instalado (7.4 ou superior)
- Servidor embutido do PHP ou Apache/Nginx

### Passos

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
Navegue até a pasta do projeto:
  ```bash
cd projeto
```

Inicie o servidor PHP:
  ```bash
  php -S localhost:8000 -t router.php
```

Acesse no navegador:
```bash
http://localhost:8000
```
