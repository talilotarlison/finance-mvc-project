# 📦 CHANGELOG

Todas as alterações importantes deste projeto serão documentadas aqui.

Este projeto segue o formato [SemVer](https://semver.org/lang/pt-BR/).

---

## [1.0.0] - 2025-09-13

### 🚀 Lançamento Inicial

- Estrutura base do projeto em PHP puro com SQLite
- Implementação do padrão MVC:
  - `Model`, `View` e `Controller` organizados em pastas separadas
- Roteador simples baseado na URL (`index.php`)
- Conexão com banco SQLite utilizando PDO
- CRUD básico de usuários
- View em HTML com dados dinâmicos
- README.md detalhado
- Licença MIT adicionada

---

## [1.0.1] - 2025-09-14

### ✨ Adicionado

- Arquivo `CHANGELOG.md`
- Função para listar todos os usuários na Home
- Mensagens de erro básicas para conexão com o banco

### 🛠️ Corrigido

- Corrigido bug onde controller não era chamado corretamente com URL minúscula

---

## [1.1.0] - 2025-09-20

### ✨ Adicionado

- Suporte a criação de novos usuários (formulário e validação)
- Feedback visual de sucesso e erro na View

### 📦 Alterado

- Melhorias na organização das views
- Separação entre layout principal e conteúdo da view

---

## [1.2.0] - EM DESENVOLVIMENTO

### ✨ Planejado

- Sistema de login e autenticação
- Migração de banco via script PHP
- Proteção contra CSRF em formulários
