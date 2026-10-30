# 🎃 Portal Halloween | Filmes e Séries de Terror

## 📌 Sobre o projeto

O Portal Halloween é um projeto desenvolvido como atividade prática do Trabalho Final de Git e GitHub.

O objetivo é criar um pequeno portal sobre filmes e séries de terror, utilizando HTML, CSS e JavaScript, além de praticar o controle de versões com Git e GitHub.

## 🎯 Objetivo

Desenvolver um site com páginas de filmes, séries e cadastro demonstrativo, aplicando os principais conceitos de versionamento de código, organização de branches, commits, merges e Pull Requests.

## 💻 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Git
- GitHub
- Visual Studio Code

## 📂 Estrutura do projeto

```text
Trab_final/
│
├── index.html       # Página inicial do portal
├── series.html      # Página com sugestões de séries
├── cadastro.html    # Página de cadastro demonstrativo
├── Readme.md        # Documentação do projeto
└── .gitignore       # Arquivos ignorados pelo Git
```

## 🌐 Páginas do projeto

### 🏠 Página inicial (index.html)
Apresenta o Portal Halloween, com uma introdução ao tema e sugestões fictícias de filmes de terror.

### 📺 Página de séries (series.html)
Apresenta três sugestões de séries:
- Stranger Things
- A Maldição da Residência Hill
- Wandinha

### 🦇 Página de cadastro (cadastro.html)
Contém um formulário demonstrativo para registrar o nome, e-mail, gênero favorito e indicação de filme ou série.

**Observação:** o formulário não envia nem armazena dados. Ele funciona apenas como demonstração.

## 🚀 Como executar o projeto

1. Baixe ou clone este repositório.
2. Abra a pasta `Trab_final` no Visual Studio Code.
3. Localize o arquivo `index.html`.
4. Abra o arquivo no navegador.
5. Navegue pelas páginas utilizando o menu do portal.

## 🌿 Organização das branches

O projeto utiliza branches para organizar o desenvolvimento:

| Branch | Função |
|---|---|
| `main` | Versão principal e final do projeto. |
| `develop` | Integração das funcionalidades. |
| `feature/series` | Desenvolvimento da página de séries. |
| `feature/cadastro` | Desenvolvimento da página de cadastro. |
| `fix/correcao` | Correção do texto da página inicial e resolução de conflito. |

## 🔀 Pull Requests e integração

As funcionalidades são desenvolvidas separadamente e depois integradas por meio de Pull Requests no GitHub.

O processo de integração segue esta ordem:

1. `feature/series` → `develop`
2. `feature/cadastro` → `develop`
3. `develop` → `main`

A branch `fix/correcao` é integrada localmente à `develop`, após a resolução do conflito de código.

## 🏷️ Histórico de versões

| Versão | Descrição |
|---|---|
| `v0.1.0` | Versão inicial, contendo a página principal, README e .gitignore. |
| `v1.0.0` | Versão completa, com as páginas de séries e cadastro e a correção de conflito. |


