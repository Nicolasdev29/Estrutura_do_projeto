# Estrutura_do_projeto

/chamados-app  
│  
├── /backend/       # Servidor, APIs e integração com banco de dados  
├── /frontend/      # Aplicação web  
├── /mobile/        # Aplicação mobile  
├── /docs/          # Documentação detalhada  
├── /tests/         # Testes automatizados  
└── README.md       # Documentação principal

### Requisitos Funcionais

*   **RF1:** Gestão de Chamados: Registrar, acompanhar status, listar, atualizar status e registrar soluções.
*   **RF2:** Inteligência Artificial: Analisar, classificar, sugerir soluções, avaliar prioridade, encaminhar chamados e aprender com soluções.
*   **RF3:** Gerenciamento de Usuários: Cadastrar colaboradores, definir hierarquia e notificar sobre novos chamados.
*   **RF4:** Gerar Relatórios: Mostrar chamados dos últimos 5, 7 e 15 dias, quantidade de chamados resolvidos e pendentes.
*   **RF5:** Gerenciar Notificações: Exibir número de notificações e notificar funcionários sobre novos chamados.

### Requisitos Não Funcionais

*   **RNF1:** Desempenho: Resposta rápida mesmo com múltiplos chamados.
*   **RNF2:** Usabilidade: Interface intuitiva e acessível (desktop e mobile).
*   **RNF3:** Conformidade com LGPD: Garantia de privacidade dos dados pessoais.
*   **RNF4:** Disponibilidade: Sistema disponível em horário comercial, com aviso prévio para manutenção.
*   **RNF5:** Segurança: Criptografia de dados e autenticação forte.

```bash
dotnet restore
```


---

### Executar o Projeto
Siga as instruções abaixo para iniciar o backend e o frontend:

#### Backend (C#)
```bash
dotnet run --project ./src/Backend
```

#### Frontend (Node.js / React / Outro)
```bash
npm start
```

---
