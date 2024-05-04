# Sistema de Controle Bancário

Bem-vindo ao Sistema de Controle Bancário! Este é um sistema desenvolvido em Python que permite a gestão de clientes, contas correntes e a execução de diversas operações bancárias, como depósito, saque e exibição de extrato. Abaixo estão detalhes adicionais sobre o funcionamento e recursos do sistema:

## Funcionalidades Principais

### 1. Criação e Gestão de Clientes
- Você pode criar novos clientes, inserindo informações como nome, data de nascimento, CPF e endereço.
- Cada cliente pode ter uma ou mais contas associadas.

### 2. Criação e Gestão de Contas Correntes
- As contas correntes são criadas para os clientes, com números únicos e atributos como saldo, agência e histórico de transações.
- É possível definir limites para saques e número máximo de saques por dia para cada conta corrente.

### 3. Operações Bancárias
- **Depósito:** Realize depósitos em contas correntes, informando o valor desejado. A data e horário do depósito são registrados automaticamente.
- **Saque:** Efetue saques das contas correntes, observando o saldo disponível e respeitando o limite de saque e número máximo de saques diários.
- **Exibição de Extrato:** Visualize o extrato da conta, exibindo todas as transações realizadas. O extrato inclui informações como data, tipo de transação (depósito ou saque) e valor.

### 4. Registro de Transações e Histórico
- Todas as transações, incluindo depósitos e saques, são registradas automaticamente no histórico da conta corrente.
- O histórico permite visualizar todas as transações realizadas em uma determinada conta em ordem cronológica, com detalhes como data e hora da transação, tipo de transação e valor.

### 5. Funcionalidades Adicionais
- **Log de Transações:** Cada transação realizada é registrada em um arquivo de log, incluindo a data, hora, tipo de transação, argumentos utilizados e resultado da transação.
- **Menu Interativo:** O sistema apresenta um menu interativo que permite ao usuário escolher facilmente entre as diferentes operações disponíveis.

## Utilização
1. **Execução do Programa:**
   - Execute o programa Python para iniciar o sistema.
   - O menu interativo será exibido, permitindo que você escolha as operações desejadas.

2. **Criação de Clientes e Contas:**
   - Crie novos clientes inserindo suas informações básicas, como nome, data de nascimento, CPF e endereço.
   - Para cada cliente, é possível adicionar uma ou mais contas correntes.

3. **Operações Bancárias:**
   - Realize depósitos informando o valor desejado.
   - Efetue saques considerando o saldo disponível e os limites estabelecidos.
   - Visualize o extrato da conta para verificar todas as transações realizadas.

4. **Registro e Log de Transações:**
   - Todas as transações realizadas são registradas no histórico da conta corrente.
   - Além disso, cada transação é registrada no arquivo de log, permitindo o acompanhamento e auditoria das operações realizadas.

5. **Menu Interativo:**
   - Utilize o menu interativo para navegar entre as diferentes funcionalidades oferecidas pelo sistema.
   - O menu facilita a execução das operações bancárias e a gestão das contas e clientes.

Este sistema foi desenvolvido para oferecer uma experiência completa de controle bancário, com funcionalidades robustas e recursos de registro e acompanhamento detalhados. Espero que aproveite sua utilização!
