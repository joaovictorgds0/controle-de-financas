# Sistema de Controle de Transações Financeiras

Este projeto é uma aplicação web simples para controle de transações financeiras, permitindo que o usuário registre, edite, exclua e visualize transações com um saldo dinâmico. O saldo é recalculado automaticamente sempre que uma transação é adicionada, modificada ou excluída. A aplicação utiliza o **JSON Server** como backend para simular uma API RESTful.

## Funcionalidades

- **Adicionar transações**: Registre transações de crédito e débito com descrição e valor.
- **Editar transações**: Modifique transações existentes.
- **Excluir transações**: Remova transações da lista.
- **Saldo dinâmico**: O saldo é recalculado automaticamente sempre que uma transação é adicionada, editada ou excluída.
- **Armazenamento no backend**: As transações e o saldo são armazenados em um banco de dados simulado usando JSON Server.

## Tecnologias Utilizadas

- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Backend**: JSON Server (para simulação de uma API RESTful)
- **Formatação de Moeda**: `Intl.NumberFormat` para exibir valores monetários no formato brasileiro (R$).

