# Matriz multicloud por pergunta

Compare decisões e evidências antes de comparar nomes de serviços. Esta matriz é um roteiro de avaliação, não uma implementação de IaC.

| Pergunta | AWS | Azure | Google Cloud | Evidência a coletar |
|---|---|---|---|---|
| Quem pode agir? | Revisar políticas e relações de confiança | Revisar papéis e identidades | Revisar vínculos de papéis e identidades | Privilégios efetivos e condições |
| Quem agiu? | Validar auditoria de ações | Validar auditoria de ações | Validar auditoria de ações | Evento com sujeito, recurso, ação e resultado |
| O dado está exposto? | Testar política e caminho de acesso | Testar política e caminho de acesso | Testar política e caminho de acesso | Acesso permitido e negado |
| Como recuperar? | Verificar cópia e restauração | Verificar cópia e restauração | Verificar cópia e restauração | Teste funcional e dependências |

## Documentar diferenças

Para cada provedor, registre escopo do controle, herança, identidade, região, logs habilitados, retenção e custo. Não presuma que serviços com nomes parecidos tenham o mesmo comportamento.

## Rota Microsoft

Implementações e consultas específicas ficam no projeto [Azure](https://github.com/Ridd1kulusC0d3r/Azure). Os pilares oficiais de AWS e Google Cloud estão nas [referências](REFERENCIAS.md).
