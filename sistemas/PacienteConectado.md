# Paciente Conectado / Multichat

Mapeamento dos canais de interacção directa, auto-atendimento e atendimento multicanal.

| Módulo Principal | Submódulo / Funcionalidade | Descrição / Exemplo de Aplicação | Observações Técnicas |
| :--- | :--- | :--- | :--- |
| **WhatsApp Oficial** | API Oficial Meta | Quedas de ligação, expiração de templates e mensagens | Provedor BSP / Meta API |
| **Chatbot / Triagem** | Fluxos de Atendimento | Árvores de resposta automática, triagem e encaminhamento| Regras de transição |
| **Fila de Atendimento** | Distribuição para Atendentes| Distribuição de chamados conforme especialidade/carteira| Filas de espera |
| **Histórico de Conversas**| Registo da Mensagem | Vinculação do diálogo directamente ao protocolo do Contatus| Histórico de chat |
| **Confirmação Automatizada**| Disparo de Confirmação | Reconhecimento de respostas de "Sim", "Não" e reagendamento| Gatilhos em lote |
