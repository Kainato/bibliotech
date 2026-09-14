# 📚 Bibliotech

## 🎯 Sobre o Projeto

O **Bibliotech** nasceu da necessidade de centralizar, catalogar e estruturar experimentos, provas de conceito (PoCs), estruturas de projetos e algoritmos isolados que antes ficavam esquecidos em repositórios soltos. 

Em vez de acumular projetos abandonados, este repositório atua como um **hub de conhecimento e referência técnica**: um guia prático para rápida consulta, reutilização de snippets testados e registro da evolução em diferentes tecnologias e padrões de arquitetura.

---

## 🛠️ O que você encontra aqui?

O acervo é organizado em categorias modulares para facilitar a navegação:

- 🏗️ **Arquiteturas & Boilerplates:** Estruturas base prontas para iniciar projetos (Clean Architecture, DDD, Modular, MVC, etc.).
- 💡 **PoCs & Experimentos:** Provas de conceito testando novas bibliotecas, pacotes, integrações e rotas de APIs.
- ⚡ **Snippets & Utilitários:** Trechos de código performáticos e reutilizáveis para tarefas recorrentes (tratamento de exceções, manipulação de dados, parsers).
- 🧩 **Design Patterns & Algoritmos:** Implementações práticas de padrões de projeto e desafios de lógica.
- 📝 **TIL (Today I Learned):** Anotações rápidas e cheatsheets sobre comandos, configurações e sacadas técnicas.

---

## 📂 Estrutura do Repositório

```text
bibliotech/
├── 📂 .vscode/              # Configurações do VS Code
├── 📂 blog/                 # Artigos, posts e registros de aprendizados
├── 📂 docs/                 # Documentações e módulos de conhecimento
├── 📂 src/                  # Componentes React, páginas e estilos do Docusaurus
│   ├── 📂 components/
│   ├── 📂 css/
│   └── 📂 pages/
├── 📂 static/               # Imagens, arquivos estáticos e assets
│   ├── 📂 docs/
│   └── 📂 img/
├── 📄 docusaurus.config.ts   # Configurações principais do Docusaurus
├── 📄 sidebars.ts            # Estrutura de navegação da barra lateral
├── 📄 package.json           # Dependências e scripts do projeto
└── 📄 README.md              # Documentação principal
```

## 🔍 Como Navegar e Reutilizar

Cada pasta neste repositório contém seu próprio arquivo README.md explicativo contendo:

1. Contexto / Problema: Qual problema essa PoC ou snippet resolve.
2. Tecnologias: Linguagens, frameworks e versões utilizadas.
3. Como Rodar: Comandos simples para testar o código localmente.
4. Aprendizados Claves: Principais pontos de atenção, trade-offs ou pegadinhas identificadas.
