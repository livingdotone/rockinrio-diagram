# Diagrama

Fluxo básico:

1. O usuário passa pela autenticação e entra na fila
2. Quando chega sua vez, verifica se há ingressos disponíveis
3. Se há ingressos disponíveis, o sistema de reservas é chamado
4. O usuário é redirecionado para o serviço de pagamento
5. Caso sucesso, o serviço de confirmação de venda é chamado
6. Caso alguma falha, o serviço de liberação de reservas é chamado