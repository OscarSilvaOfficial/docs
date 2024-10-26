# Casos de Uso

## UC-001: Login do Usuário
- **Descrição**: O usuário acessa o sistema com suas credenciais.
- **Ator**: Usuário
- **Pré-condições**: O usuário deve estar registrado.
- **Fluxo Principal**:
  1. Usuário insere nome e senha.
  2. Sistema verifica as credenciais.
  3. Acesso liberado em caso de sucesso.
- **Fluxos Alternativos**:
  - Caso as credenciais sejam inválidas, exibir uma mensagem de erro e solicitar nova tentativa.
- **Pós-condições**: Usuário autenticado e acesso concedido.

### Campos
- **ID**: Código único do caso de uso.
- **Nome**: Nome do caso de uso.
- **Descrição**: Propósito do caso de uso.
- **Ator**: Quem interage com o sistema.
- **Pré-condições**: Estado inicial necessário para o caso de uso.
- **Fluxo Principal**: Passos para completar o caso de uso.
- **Fluxos Alternativos**: Outros caminhos possíveis.
- **Pós-condições**: Estado final do sistema.
