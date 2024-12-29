# Fokus - Gerenciador de Produtividade

**Fokus** é um aplicativo web que combina um temporizador de produtividade (baseado na técnica Pomodoro) com um sistema de gerenciamento de tarefas. Ele ajuda os usuários a manterem o foco em suas atividades, equilibrando momentos de trabalho intenso com pausas curtas e longas.

## 📋 Funcionalidades

- **Temporizador Personalizado**:
  - Modos de foco, descanso curto e descanso longo.
  - Sons de notificação para início e fim dos períodos.
- **Gerenciamento de Tarefas**:
  - Adicionar, editar e remover tarefas.
  - Marcar tarefas como concluídas.
  - Persistência de dados no navegador usando `localStorage`.
- **Interatividade e Interface Responsiva**:
  - Interface intuitiva para desktop e dispositivos móveis.
  - Alternância entre temas de fundo de acordo com o contexto ativo (foco ou descanso).

## 🚀 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível.
- **CSS3**: Design responsivo e estilização dinâmica.
- **JavaScript**: Funcionalidades interativas e manipulação do DOM.
  - `script.js`: Gerencia o temporizador e as interações relacionadas ao contexto.
  - `script-crud.js`: Controla as operações CRUD das tarefas.
- **LocalStorage**: Persistência local dos dados das tarefas.