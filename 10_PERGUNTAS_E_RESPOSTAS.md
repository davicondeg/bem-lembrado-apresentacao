# Perguntas prováveis da professora

## 1. O sistema já está funcionando?

**Resposta:** O que temos nesta etapa é o protótipo visual e o planejamento completo do MVP. A integração funcional entre painel, banco, automação e WhatsApp faz parte da segunda etapa. Por isso, os fluxos e dados mostrados são simulações do comportamento esperado.

## 2. Por que usar WhatsApp em vez de criar um aplicativo?

**Resposta:** Porque o projeto busca reduzir a barreira de adoção. O WhatsApp já faz parte da rotina de muitos usuários idosos, enquanto um aplicativo novo exigiria instalação, cadastro e aprendizagem de outra interface. O painel separado atende ao responsável.

## 3. A solução substitui familiares ou cuidadores?

**Resposta:** Não. Ela apoia tarefas repetitivas de acompanhamento e facilita a comunicação. O objetivo é fortalecer autonomia e rede de apoio, sem substituir cuidado humano, orientação médica ou atendimento de emergência.

## 4. Como vocês evitam que a IA forneça orientação médica?

**Resposta:** Regras críticas não dependem da IA. O sistema deve bloquear diagnóstico, prescrição e alteração de dose, utilizar respostas limitadas ao escopo e direcionar situações sensíveis para o responsável ou serviço adequado. Também estão previstos testes negativos e registros para auditoria.

## 5. Como a LGPD será tratada?

**Resposta:** Com consentimento explícito, minimização de dados, controle de acesso por responsável, autenticação, políticas de segurança no banco, registro de operações e possibilidade de revogação. Somente contatos autorizados poderão acompanhar informações.

## 6. O que acontece se o idoso não responder?

**Resposta:** A ausência de resposta não é tratada automaticamente como emergência. Após o prazo e as tentativas configuradas, o sistema registra a não confirmação e pode alertar um contato autorizado, conforme a regra definida pelo responsável.

## 7. Como chegaram ao valor de R$ 16,9 mil?

**Resposta:** A estimativa reúne custo de mão de obra das 175 horas previstas, custos fixos e variáveis dos serviços e uma reserva de contingência. O detalhamento está na documentação. É uma estimativa acadêmica do esforço do projeto, não o preço final de um produto comercial.

## 8. O que significam os 144 pontos de função?

**Resposta:** É uma estimativa preliminar do tamanho funcional do sistema baseada nas funções percebidas pelo usuário, como entradas, consultas, saídas e dados mantidos. Ela ajuda a comparar escopo e esforço, mas deve ser refinada conforme os requisitos forem implementados.

## 9. Por que o projeto é considerado viável se depende da Meta?

**Resposta:** Ele é viável para prototipação e demonstração porque existem APIs e webhooks documentados. Entretanto, a dependência da Meta é um risco real e foi registrada. Uma implantação em produção exige credenciais, aprovação, acompanhamento de políticas e revisão contínua de custos e limites.

## 10. Por que escolheram Scrum e Kanban juntos?

**Resposta:** O Scrum adaptado organiza objetivos e revisões semanais. O Kanban oferece visibilidade diária do estado das tarefas, responsáveis e bloqueios. A combinação atende melhor a uma equipe acadêmica pequena e a um prazo curto.

## 11. Como os usuários serão escolhidos para o piloto?

**Resposta:** A previsão é trabalhar com 10 a 20 pessoas idosas que já utilizem WhatsApp e seus responsáveis, preferencialmente na Grande Vitória. A participação dependerá de convite, consentimento e critérios éticos definidos antes da validação.

## 12. Como vocês medirão o sucesso?

**Resposta:** Por indicadores como taxa de lembretes confirmados, tempo médio de resposta, capacidade de concluir o fluxo sem ajuda e satisfação dos participantes. Também serão observados erros, desistências e dificuldades de compreensão.

## 13. E se o usuário não souber ler ou tiver limitações visuais?

**Resposta:** O público inicial pressupõe capacidade básica de ler e responder mensagens. Para ampliar a inclusão, versões futuras podem avaliar áudio, mensagens de voz, fontes e configurações de acessibilidade. Isso não foi incluído no MVP para manter o escopo controlado.

## 14. Qual é o maior risco do projeto?

**Resposta:** Há dois riscos especialmente críticos: privacidade dos dados e uso inadequado da IA. Ambos têm impacto muito alto. Por isso, consentimento, controle de acesso e regras determinísticas fora da IA são condições para avançar.

## 15. Qual é a principal inovação da proposta?

**Resposta:** A proposta integra lembretes, confirmação, histórico e acompanhamento autorizado em um canal familiar ao usuário idoso. O diferencial não é apenas enviar uma mensagem, mas fechar o ciclo entre configuração, interação e acompanhamento.

## 16. O que acontece se a Internet ou um serviço externo falhar?

**Resposta:** O sistema deve registrar a falha, realizar tentativas controladas e informar o responsável quando a entrega não puder ser confirmada. Dependências externas e disponibilidade fazem parte dos requisitos não funcionais e do plano de riscos.

## Regra para perguntas difíceis

Se a equipe não souber uma resposta, utilizar:

> Esse ponto ainda não foi validado na etapa atual. Nós o registraríamos como premissa ou risco e faríamos a verificação antes da implantação.

Evitar inventar resultados, testes, entrevistas ou funcionalidades que não foram realizados.
