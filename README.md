# 📋 Gerenciador de Tarefas

Projeto desenvolvido em React como atividade prática da disciplina de Desenvolvimento Web, com o objetivo de aplicar conceitos de componentização, gerenciamento de estado, manipulação de eventos e Context API.

## 🚀 Sobre o Projeto

O Gerenciador de Tarefas é uma aplicação web que permite ao usuário:

* Adicionar novas tarefas;
* Marcar tarefas como concluídas;
* Filtrar tarefas por status;
* Excluir tarefas;
* Limpar tarefas concluídas;
* Visualizar estatísticas das tarefas;
* Manter as tarefas salvas no navegador utilizando LocalStorage.

O projeto foi desenvolvido utilizando React e Context API para gerenciamento global de estado, promovendo uma arquitetura organizada e escalável.

---

## 🛠️ Tecnologias Utilizadas

* React JS
* JavaScript (ES6+)
* Vite
* HTML5
* CSS3
* Context API
* useReducer
* useState
* useEffect
* LocalStorage

---

## 📂 Estrutura do Projeto

```text
gerenciador-tarefas/
│
├── public/
│
├── src/
│   ├── components/
│   │   ├── ListaDeTarefas.jsx
│   │   └── Tarefa.jsx
│   │
│   ├── context/
│   │   └── TarefaContext.jsx
│   │
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
├── vite.config.js
└── README.md
```

---

## ⚙️ Funcionalidades

### Adicionar Tarefa

O usuário pode digitar o nome de uma tarefa em um campo de texto e adicioná-la à lista através do botão "Adicionar" ou pressionando a tecla Enter.

### Marcar como Concluída

Cada tarefa possui uma caixa de seleção (checkbox) que permite alterar seu status entre concluída e pendente.

### Filtrar Tarefas

A aplicação disponibiliza filtros para exibir:

* Todas as tarefas;
* Apenas tarefas concluídas;
* Apenas tarefas pendentes.

### Excluir Tarefa

Permite remover uma tarefa específica da lista.

### Limpar Concluídas

Remove todas as tarefas marcadas como concluídas.

### Persistência de Dados

As tarefas permanecem armazenadas mesmo após fechar ou atualizar a página, utilizando LocalStorage.

### Estatísticas

A aplicação apresenta:

* Quantidade total de tarefas;
* Quantidade de tarefas concluídas;
* Quantidade de tarefas pendentes.

---

## 🧠 Conceitos Aplicados

Durante o desenvolvimento foram utilizados os seguintes conceitos do React:

### Componentização

Separação da aplicação em componentes reutilizáveis:

* App
* ListaDeTarefas
* Tarefa

### useState

Utilizado para controlar estados locais, como:

* Campo de entrada de texto;
* Filtro selecionado.

### useContext

Responsável por disponibilizar o estado global para todos os componentes da aplicação.

### useReducer

Utilizado para centralizar e organizar as ações relacionadas às tarefas.

Ações implementadas:

* ADICIONAR
* TOGGLE
* EXCLUIR
* LIMPAR_CONCLUIDAS

### useEffect

Utilizado para salvar automaticamente as alterações no LocalStorage.

### Atualização Imutável de Estado

Todas as alterações da lista são realizadas sem modificar diretamente o estado original, seguindo as boas práticas do React.

---

## 📥 Instalação

Acesse a pasta do projeto:

```bash
cd gerenciador-tarefas
```

Instale as dependências:

```bash
npm install
```

Execute o projeto:

```bash
npm run dev
```

A aplicação estará disponível em:

```text
http://localhost:5173
```

---

## 🔮 Melhorias Futuras

Possíveis evoluções para o projeto:

* Edição de tarefas;
* Categorias de tarefas;
* Prioridades (Alta, Média e Baixa);
* Tema claro/escuro;
* Integração com banco de dados;
* Autenticação de usuários;
* Deploy em ambiente cloud.

---

## 👨‍💻 Autor
- Jullia Karolina de Paula
- julliakarolinadev@gmail.com

Projeto desenvolvido para fins acadêmicos como prática dos conceitos fundamentais de React JS, Context API e gerenciamento de estado em aplicações front-end.
