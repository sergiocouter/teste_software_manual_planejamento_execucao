# Módulo 3 - Teste de Software no Ágil

## 1. Estratégias de Testes para o Ágil

### 1.1. Testes Baseados em Risco
- **Objetivo**: Priorizar testes com base nos riscos para o negócio.
- **Exemplo**: Para a funcionalidade de login:
  - **Alta severidade**: Usuário não consegue logar.
  - **Média severidade**: Exibição incorreta de erro de login.
  - **Baixa severidade**: Problemas cosméticos na interface.

### 1.2. Testes Regressivos Automatizados
- **Importância**: Automatizar testes críticos que asseguram a continuidade de funcionalidades importantes.
- **Exemplo**: Testes de login, funcionalidades essenciais para o cliente.

### 1.3. Testes Reativos
- **Exploratórios**: Não exigem documentação e são realizados de forma dinâmica.
- **Objetivo**: Encontrar defeitos inesperados durante a exploração do sistema.

---

## 2. Construindo um Processo de Teste no Ágil

### 2.1. Planejamento Ágil
- **Foco**: Planejamento macro, com ferramentas simples como planilhas e checklists.
- **Objetivo**: Realizar o trabalho com **agilidade** e **automação**.

### 2.2. Plano de Teste
- A qualidade é responsabilidade do time como um todo.
- O **QA** traz **estratégias**, **técnicas** e **tipos de testes** que devem ser implementados, discutindo com o time o que será feito.

---

## 3. Papéis no Ágil

Dentro do contexto ágil, os papéis são fundamentais para o sucesso do time:

- **Testador Ágil (QA)**:
  - **Responsabilidades**: Garantir a qualidade do sistema ao longo de todo o ciclo de desenvolvimento.
  - **Atividades**: Planejamento de testes, execução contínua, e feedbacks rápidos.

- **Desenvolvedor**: Responsável por criar e validar o código.
- **Cliente**: Realiza testes sob a perspectiva da funcionalidade.

---

## 4. Automação no Ágil

### Desafios:
- **Automatizar o cenário correto**: Escolher bem o que automatizar, garantindo que testes repetitivos sejam feitos automaticamente, aumentando a eficiência.
- **Evitar inteligência na automação**: Automação deve ser para **testes repetitivos**, não para lógica de negócios.

### Objetivo da Automação:
- **Agilidade**: Acelerar o ciclo de testes.
- **Segurança**: Garantir que a aplicação não quebre ao realizar alterações no código.

---

## 5. Integração Contínua

- **CI/CD (Integração Contínua e Deploy Contínuo)**: Permite que os testes automatizados sejam executados sempre que o código for alterado, garantindo que não haja falhas inesperadas nas funcionalidades existentes.
- **Métricas**: Cobertura de testes, saúde do código e dependências.

---

## Conclusão

Este módulo abordou a importância dos testes dentro do contexto ágil e como eles são fundamentais para o sucesso do ciclo de desenvolvimento. As metodologias ágeis e a integração contínua são aliadas poderosas para garantir que o software entregue seja de alta qualidade, com entregas rápidas e incrementais.

