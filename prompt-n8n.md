Atue como um especialista em N8N.

Crie uma automação para enviar lembretes de cobrança por WhatsApp aos clientes com pagamento próximo do vencimento.

Público:
Responsável pelo financeiro.

Ferramentas envolvidas:
N8N, Google Sheets e UZAPI (API de WhatsApp).

Fluxo:
Todo dia às 9h, ler a planilha de pagamentos, filtrar os clientes com vencimento em até 3 dias e status "pendente", enviar uma mensagem personalizada pelo WhatsApp (UZAPI) e registrar a data do envio na planilha.

Regras:
Ignorar clientes sem telefone válido.
Não enviar duas vezes no mesmo dia para o mesmo cliente.
Continuar o fluxo mesmo que um envio falhe.

Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.
